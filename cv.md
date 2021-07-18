# Vasily Cherevko

## Contact Information:
- Stary Oskol, Russia
- **Telegram:** [Venzard](http://t.me/venzard)
- **Discord:** Venzard#2370

## Short info:
I want to get professional skills in frontend development. I think this area is interesting and promising.
## Skills:
- HTML, CSS
- Python

## Code examples:
```python
def main(): 
    driver = webdriver.Chrome()
    driver.get("https://vk.com/")
    driver.set_window_size(1920, 1024) 
    usernameForm = driver.find_element_by_id("index_email")
    usernameForm.send_keys('login_vk')
    passwordForm = driver.find_element_by_id("index_pass")
    passwordForm.send_keys('pass_vk')
    loginButton = driver.find_element_by_id('index_login_button')                                       
    loginButton.click()                                                                            
#откр сохр
    driver.get("https://vk.com/album"id"_000") 
    time.sleep(2.5) 
    driver.find_element_by_class_name("photos_row ").click()
    time.sleep(2.5) 
#лайк
    for i in range(0, 40): //кол-во фото
        driver.find_element_by_class_name("like_button_icon").click()
#след
        select = driver.find_element_by_class_name("pv_fs_wrap")
        ActionChains(driver).move_to_element_with_offset(select, 0, 150).click().perform()
        time.sleep(0.5)
        print(i)
    driver.find_element_by_class_name("pv_close_btn").click()
    time.sleep(2.5)
    driver.quit()
if __name__ == "__main__":
        main()
```
## Work:
I work in sap consulting.
## Education:
#### Moscow Aviation Institute
Faculty No. 3 "Control Systems, Informatics and Power Engineering", Graduate, 2017.
### Languages:
- English (B1)
- Russian (native)