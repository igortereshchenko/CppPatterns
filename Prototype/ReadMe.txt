﻿Назначение
Для создания новых объектов паттерн Prototype использует прототипы. 
Прототип - это уже существующий в системе объект, который поддерживает операцию клонирования, 
то есть умеет создавать копию самого себя. Таким образом, для создания объекта некоторого 
класса достаточно выполнить операцию clone() соответствующего прототипа.

Применимость
Паттерн используется чтобы:

	 - избежать дополнительных усилий по созданию объекта стандартным путём (имеется в виду использование 
	конструктора, так как в этом случае также будут вызваны конструкторы всей иерархии предков объекта), 
	когда это непозволительно дорого для приложения.
	 - избежать наследования создателя объекта (object creator) в клиентском приложении, как это делает паттерн 
	abstract factory.
	 - Используйте этот шаблон проектирования, когда системe безразлично как именно в ней создаются, 
	компонуются и представляются продукты:
		 - инстанцируемые классы определяются во время выполнения, например с помощью динамической загрузки;
		 - избежать построения иерархий классов или фабрик, параллельных иерархии классов продуктов;
		 - экземпляры класса могут находиться в одном из нескольких различных состояний. 


Задача на самостоятельную работу
Расширить существующий код новым классом “StudentRecord”, что содержит два текстовых поля: номер зачетки и имя студента.
