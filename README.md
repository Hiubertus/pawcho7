# pawcho7

Zacząłem od zalogowania się na konsoli do DockerHub, następnei wykorzystałem przykładowy kod z zadania 5.
![image](https://github.com/Hiubertus/pawcho7/assets/138579706/ea13523b-2183-4357-8124-5d9aa13c8634)

Nastepnie zbudowałem obraz nastepującym poleceniem.
![image](https://github.com/Hiubertus/pawcho7/assets/138579706/6e3204fe-6e15-4f5c-a660-2dce00d198ac)

By sprawdzić stworzenie się obrazów i cache, wykorzystałem docker manifest inspect.
![image](https://github.com/Hiubertus/pawcho7/assets/138579706/9f75fe8c-be68-4902-a226-9e172f3b5264)

Nastepnie sprawdziłem na stronie DockerHub czy obraz został wysłany
![image](https://github.com/Hiubertus/pawcho7/assets/138579706/f7a58436-a0f8-4b3f-b0cb-1c0c1648ea3e)

Przy pierwszym stworzeniu obrazu był bład spowodowany tym, że nie dało się pobrac cache z DockerHub, gdy jednak uruchomiłem budowanie ponownie, ten błąd zanikł, co oznacza, że cache zostało pobrane.
![image](https://github.com/Hiubertus/pawcho7/assets/138579706/d64c72cf-58f4-465a-8fb6-e50a499b278d)
