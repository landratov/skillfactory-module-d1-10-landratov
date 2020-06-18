Перед использование заполните параметры авторизации и id вашей доски (в длинном формате)

  auth_params = {    
      'key': "",    
      'token': "", }
  
  board_id = ""

Возможные команды:

  create - создание новой карточки в определенном списке. Пример: python trello-d1.py create "TaskName" "ListName"
  
  move - перемещение карточки в определенный список. Пример: python trello-d1.py move "TaskName" "ListName"
  
  addlist - создание нового списка. Пример: python trello-d1.py addlist "ListName"
