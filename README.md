
from selenium import webdriver
from time import sleep
import pyautogui
import time
import itertools


#LOGIN WINS!

driver = webdriver.Chrome()
driver.get(url='https:// login')
time.sleep(2)
search = driver.find_element_by_id("user")
search.send_keys('mrosuite')
search = driver.find_element_by_id("password")
search.send_keys('senha')

time.sleep(2)
search = driver.find_element_by_id("loginButton")
time.sleep(1)
pyautogui.press('enter')

#TAKS - COMPONENTES

time.sleep(2)
driver.get("https://")
time.sleep(2)
search = driver.find_element_by_id("sewbutton-1042-btnInnerEl").click()
time.sleep(2)
pyautogui.write('arquivo_salvo_inspeções')
pyautogui.press('enter')
pyautogui.press('tab')
pyautogui.press('tab')
pyautogui.press('tab')
pyautogui.press('tab')
pyautogui.press('enter')
search = driver.find_element_by_id("btnothers-btnIconEl").click()
time.sleep(2)
pyautogui.press('tab')
time.sleep(1)
pyautogui.press('enter')
time.sleep(1)
pyautogui.press('right')
time.sleep(1)
pyautogui.press('right')
time.sleep(1)
pyautogui.press('tab')
time.sleep(1)
pyautogui.write('Contrato Colombia encerrado')
pyautogui.press('tab')
pyautogui.press('enter')
time.sleep(2)
    

#TASK - LOOPING

def loop():
    
    search = driver.find_element_by_id("btnothers-btnIconEl").click()
    time.sleep(2)
    pyautogui.press('tab')
    time.sleep(1)
    pyautogui.press('enter')
    time.sleep(1)
    pyautogui.press('right')
    time.sleep(1)
    pyautogui.press('right')
    time.sleep(1)
    pyautogui.press('tab')
    time.sleep(2)
    pyautogui.write('Contrato Colombia encerrado')
    pyautogui.press('tab')
    pyautogui.press('enter')
    time.sleep(2)
  
x=1

while (x>=1):
        loop()
