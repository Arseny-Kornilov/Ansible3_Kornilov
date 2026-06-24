# Домашнее задание к занятию «Создание собственных модулейs»

## Шаг 4. Проверьте module на исполняемость локально.
### Проверка осуществлялась командой ANSIBLE_LIBRARY=. ansible localhost -m my_module -a "path=/tmp/test.txt content='Test'" -c local
<img width="828" height="142" alt="image" src="https://github.com/user-attachments/assets/005251a3-8d32-4f3f-8266-5a2c5264eb2d" />
<img width="816" height="140" alt="image" src="https://github.com/user-attachments/assets/422460c2-ea3a-431b-a5c6-12ae74551a27" />



## Шаг 6. Проверьте через playbook на идемпотентность.
### Проверка осуществлялась командой ANSIBLE_LIBRARY=. ansible-playbook test_module.yml -c local -e "ansible_python_interpreter=/usr/bin/python3"
<img width="819" height="124" alt="image" src="https://github.com/user-attachments/assets/94b77c29-0cb4-45f5-94a2-46205814dfce" />
<img width="817" height="128" alt="image" src="https://github.com/user-attachments/assets/7cb88813-073c-47ce-99d6-c4126ab348bd" />

