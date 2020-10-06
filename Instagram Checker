{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 108,
   "metadata": {},
   "outputs": [],
   "source": [
    "from selenium import webdriver\n",
    "from bs4 import BeautifulSoup\n",
    "from time import sleep"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 132,
   "metadata": {},
    }
   ],
   "source": [
    "browser = webdriver.Chrome(\"chromedriver.exe\")\n",
    "browser.get(\"https://www.instagram.com/?hl=en\")\n",
    "#..............................................................................\n",
    "sleep(10)\n",
    "user = input(\"Enter User Name:-->\")\n",
    "passwd = input(\"Enter Password:-->\")\n",
    "user_name = browser.find_element_by_name(\"username\")\n",
    "user_name.send_keys(user)\n",
    "password = browser.find_element_by_name(\"password\")\n",
    "password.send_keys(passwd)\n",
    "browser.find_element_by_class_name(\"Igw0E\").click()\n",
    "\n",
    "#..............................................................................\n",
    "try:\n",
    "    sleep(10)\n",
    "    browser.find_element_by_class_name(\"sqdOP \").click()\n",
    "    sleep(5)\n",
    "    try:\n",
    "        post_off = browser.find_element_by_class_name(\"HoLwm \").click()\n",
    "    except:\n",
    "        pass\n",
    "    sleep(10)\n",
    "    admin = browser.find_element_by_class_name(\"gmFkV\").click()\n",
    "\n",
    "    #..............................................................................\n",
    "    sleep(10)\n",
    "    followers = browser.find_element_by_xpath(\"//ul[@class='k9GMp ']/li[@class='Y8-fY ']/a[@class='-nal3 ']\").click()\n",
    "    o = 0\n",
    "    sleep(5)\n",
    "    while True:\n",
    "        bar = browser.find_element_by_xpath('/html/body/div[4]/div/div/div[2]')\n",
    "        browser.execute_script('arguments[0].scrollTop = arguments[0].scrollHeight', bar)\n",
    "        o+=1\n",
    "        if o ==10000:\n",
    "            break\n",
    "    fol = browser.find_element_by_class_name(\"isgrP \")\n",
    "    data = BeautifulSoup(fol.get_attribute(\"innerHTML\"),\"html.parser\")\n",
    "    my_fol = data.find_all(\"a\")\n",
    "    k = []\n",
    "    for my in my_fol:\n",
    "        if my.text != \"\":\n",
    "            k.append(my.text)\n",
    "    browser.find_element_by_xpath(\"//div[@class='WaOAr']/button[@class='wpO6b ']\").click()\n",
    "\n",
    "    #..............................................................................\n",
    "    sleep(5)\n",
    "    following = browser.find_element_by_xpath(\"//*[@id='react-root']/section/main/div/header/section/ul/li[3]/a\").click()\n",
    "    sleep(5)\n",
    "    o = 0\n",
    "    while True:\n",
    "        bar = browser.find_element_by_xpath('/html/body/div[4]/div/div/div[2]')\n",
    "        browser.execute_script('arguments[0].scrollTop = arguments[0].scrollHeight', bar)\n",
    "        o+=1\n",
    "        if o ==10000:\n",
    "            break\n",
    "    fol_i = browser.find_element_by_class_name(\"isgrP \")\n",
    "    data_i = BeautifulSoup(fol_i.get_attribute(\"innerHTML\"),\"html.parser\")\n",
    "    i_fol = data_i.find_all(\"a\")\n",
    "    n = []\n",
    "    for i in i_fol:  \n",
    "        if i.text !=\"\":\n",
    "            n.append(i.text)\n",
    "\n",
    "    browser.find_element_by_xpath(\"/html/body/div[4]/div/div/div[1]/div/div[2]/button\").click()  \n",
    "    #..............................................................................\n",
    "    j =[]\n",
    "    for i in range(len(n)):\n",
    "        if n[i] not in k:\n",
    "            j.append(n[i])\n",
    "    #..............................................................................        \n",
    "    sleep(2)\n",
    "    browser.find_element_by_xpath(\"//*[@id='react-root']/section/main/div/header/section/div[1]/div[2]/button\").click()\n",
    "    #..............................................................................\n",
    "    sleep(2)\n",
    "    browser.find_element_by_xpath(\"/html/body/div[4]/div/div/div/div/button[9]\").click()\n",
    "    #..............................................................................\n",
    "    sleep(2)\n",
    "    browser.find_element_by_xpath(\"//*[@id='react-root']/section/main/article/div[2]/div[1]/div/div/div[2]/button\").click()\n",
    "    #..............................................................................\n",
    "    sleep(2)\n",
    "    browser.find_element_by_xpath(\"/html/body/div[4]/div/div/div/div[2]/button[1]\").click()\n",
    "except:\n",
    "    print(\"Enter Correct UserName and Password\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 110,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 111,
   "metadata": {},
   "outputs": [],
   "source": [
    "     "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 112,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.6"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
