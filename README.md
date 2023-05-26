Втора лабораториска вежба по Софтверско инженерство
Елена Марковска, бр. на индекс 216009

Control Flow Graph
Фотографија од control flow graph-ot
![CFG](https://github.com/Elenamarkov/SI_2023_lab2_216009/assets/127608687/78e7add8-7f7f-4b9e-917c-672e0f0d71f4)

Цикломатска комплексност
Цикломатската комплексност на овој код е 11, истата ја добив преку формулата P+1, каде што P е бројот на предикатни јазли. Во случајoв P=10, па цикломатската комплексност изнесува 11.

Тест случаи според критериумот Every statement
Statement	User = null, allUsers = any	User = User(“user”.”ab@.@”), allUsers = {}			
1	1	1			TRUE
2	0	1			TRUE
3	1	0			TRUE
4	1	1			TRUE
5	1	0			TRUE
6	1	1			TRUE
7	1	1			TRUE
8	0	1			TRUE
9.1	0	1			TRUE
9.2	0	1			TRUE
9.3	0	1			TRUE
10	0	1			TRUE
11	0	1			TRUE
12	0	1			TRUE
13	0	1			TRUE
14	0	1			TRUE
15	1	1			TRUE
16	1	1			TRUE
17	1	1			TRUE
18	1	1			TRUE
19	0	1			TRUE
20	1	0			TRUE
21	1	0			TRUE
22.1	1	0			TRUE
22.2	1	0			TRUE
22.3	1	0			TRUE
24	1	0			TRUE
25	1	0			TRUE
![image](https://github.com/Elenamarkov/SI_2023_lab2_216009/assets/127608687/670568f8-b331-4f7f-9bd5-d50c6c0c82a5)


Тест случаи според критериумот Every path
Branch	User = null, allUsers = any	User = User(“user”.”ab@.@”), allUsers = {}	User = User(“user”.”ab@”), allUsers = {}	User = User(“user”.”ab.”), allUsers = {}			
1-2	1	1	1	1			TRUE
2-3	1	0	0	0			TRUE
2-4	0	1	1	1			TRUE
3-4	1	0	0	0			TRUE
4-5	1	0	0	0			TRUE
5-6	1	0	0	0			TRUE
4-6	0	1	1	1			TRUE
6-7	1	1	1	1			TRUE
7-8	0	1	1	1			TRUE
7-15	1	1	1	1			TRUE
8-9.1	0	1	1	1			TRUE
9.1-9.2	0	1	1	1			TRUE
9.2-10	0	1	1	1			TRUE
10-11	0	1	1	1			TRUE
11-12	0	1	1	1			TRUE
11-13	0	1	1	1			TRUE
12-13	0	1	1	1			TRUE
13-14	0	1	1	1			TRUE
13-9.3	0	1	1	1			TRUE
14-9.3	0	1	1	1			TRUE
14-15	0	1	1	1			TRUE
9.3-9.2	0	1	1	1			TRUE
15-16	1	1	1	1			TRUE
16-17	1	1	1	1			TRUE
17-18	1	1	1	1			TRUE
18-19	0	1	1	1			TRUE
18-20	1	0	0	0			TRUE
19-20	1	0	0	0			TRUE
20-21	1	0	0	0			TRUE
21-25	1	0	0	0			TRUE
21-22.1	1	0	0	0			TRUE
22.1-22.2	1	0	0	0			TRUE
22.2-23	1	0	0	0			TRUE
23-24	1	0	0	0			TRUE
23-22.3	1	0	0	0			TRUE
22.3-22.2	1	0	0	0			TRUE
24-22.3	1	0	0	0			TRUE
24-25	1	0	0	0			TRUE
19-25	0	1	1	1			TRUE
![image](https://github.com/Elenamarkov/SI_2023_lab2_216009/assets/127608687/87269604-4091-4965-b31b-95342f8ee1b3)


Објаснување на напишаните unit tests
... ...
