# Зачётная работа (Игра "Астероиды")
## Цель работы:
### Научиться проектировать и строить сложные, многофайловые приложения по заданию, принимать инженерные и проектировочные решения.
## Требования к работе:
### 1. При старте игры на экране отображается:
- Начальное количество жизней 
- Начальное количество очков
- Неподвижный фон
- Динамический фон
- Заставка игры – по центру
### 2. При щелчке на заставке игра начинается. В центре игровой области появляется корабль. Также начинают генерироваться астероиды в произвольных местах игрового поля с определенной частотой.
### 3. Корабль управляется игроком с клавиатуры и может:
- Вращаться относительно своего центра
- Стрелять ракетами по направлению ориентации корабля
- Ускоряться по направлению ориентации корабля
### 4. Игровое поле имеет тороидальную геометрию, то есть при пересечении любым объектом, например, левой границы экрана он появляется с правой стороны, сохраняя направление и величину линейной и угловой скорости.
### 5. При ускорении изображение корабля должно меняться на изображение корабля с включенными двигателями. При завершении ускорения изображение должно меняться на исходное.
### 6. При выключенных двигателях корабля, он испытывает сопротивление среды и постепенно замедляется до полной остановки.
### 7. Астероиды при появлении имеют случайную линейную и угловую скорость.
### 8. Ракеты должны появляться из «носа» корабля и лететь в ту сторону, в которую ориентировано изображение корабля с постоянной скоростью.
### 9. Ракеты имеют ограниченное время жизни. По его истечении ракета исчезает с экрана. Это время жизни нужно выбрать исходя из отношения размеров экрана к скорости полета ракеты таким образом, чтобы ракета не могла пролететь все игровое поле даже по малому измерению.
### 10. При столкновении ракеты и астероида астероид и ракета исчезают с экрана, на месте астероида показывается анимация взрыва, игроку начисляется одно очко.
### 11. При столкновении корабля и астероида, астероид исчезает с экрана, на его месте показывается анимация взрыва, корабль возрождается неподвижный в середине игрового поля, количество жизней игрока уменьшается на единицу.
### 12. Если на момент смерти игрока, количество жизней равнялось 0, игра считается оконченной, на экране снова демонстрируется заставка (все астероиды, ракеты и корабль не прорисовываются), счет и количество жизней остаются на экране.
### 13. Астероиды не сталкиваются, а свободно проходят друг поверх друга. 
