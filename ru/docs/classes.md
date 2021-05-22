# Классы (Class)
## Empty
Предок:
* Нет

Переменные:
* Visible
* DrawingLayer
* Collidable
* Interactable
* CenterX
* CenterY
* Rotation
* SizeX
* SizeY
* VelocityX
* VelocityY

К этому классу принадлежат все классы, для которых не был явно указан другой класс,
а также от этого класса наследуются все классы, для которых не был явно указан другой предок
## TopDownPlayer
Предок:
* Empty

Переменные:
* TopDownSpeed

* IsXMoreImportant
* PreviousOnDiagonal
* FlipXIfNotPresent
* FlipYIfNotPresent

* StandAnimationRight
* StandAnimationLeft
* StandAnimationUp
* StandAnimationDown

* MoveAnimationRight
* MoveAnimationLeft
* MoveAnimationUp
* MoveAnimationDown

* AnimationTime

Класс игрока для игр с видом сверху. Управление на WASD, взаимодействие на E.
Так предок - Empty, обладает всеми переменными Empty
## CameraFrame
Предок:
* Нет

Переменные:
* CenterX
* CenterY
* SizeX
* SizeY

* CameraMaxYSize

Класс рамки для камеры, в которую (если у рамки не нулевые размеры) будет всегда
пытаться поместиться камера. Позволяет задать максимальную высоту камеры в пикселях
