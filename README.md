# тестовое задание на работу с массивом
###### Дан массив пользователей и статусов. У каждого пользователя есть свои статусы. Задача с помощью любой конструкции по перебору массива сформировать таблицу вида:
```
id |	name |	status
1	 | Taras | Active
2	 | Taras | Passive
3	 | Taras |-

```
## Массив данных
```
$arrayClient = [
            [
                'id' => 1,
                'name' => 'Taras',
                'status_id' => 1
            ],
            [
                'id' => 2,
                'name' => 'Taras',
                'status_id' => 2
            ],
            [
                'id' => 3,
                'name' => 'Taras',
                'status_id' => 3
            ]
        ];
        $arrayClientStatus = [
            [
                'id' => 1,
                'name' => 'Active',
            ],
            [
                'id' => 2,
                'name' => 'Passive',
            ],
        ];
```
