# Исследование данных Titanic
## Введение
Этот проект представляет собой комплексное исследование данных о выживаемости пассажиров судна "Титаник", включающее предварительный анализ данных, инженерию признаков и создание полносвязной нейронной сети для классификации. 

---

## цель исследования
попытка написать полноценное исследование на тему машинного обучения, решающее задачу классификации признака.
---

## Основные этапы работы
1. Извлечение данных из датасета
2. Проведение предварительного и разведывательного анализа данных EDA
3. Инженерия признаков
4. разработка и выбор модели, наиболее точно решающей поставленную задачу по заданной метрике

---

## методы работы
1. **Извлечение данных**: используются данные о пассажирах в формате csv
2. **Предварительный анализ данных**:
  1. Анализируется распределение выживаемости на борту в зависимости от иных признаков
  2. Исследуются корреляции между признаками в датасеты, ищутся скрытые зависимости в данных
  3. Выявляются основные гипотезы и тренды
3. **Инженерия признаков**:
  1. Преобразуются категориальные переменные в числовые
  2. Создаются новые признаки на основе существующих
  3. Выбираются наиболее важные признаки для прогнозирования выживаемости
4. **Создание модели**
  1. Разработана полносвязная нейронная сеть с несколькими слоями
  2. Использована функция активации ReLU и регуляризация
  3. Применена кросс-валидация для оценки производительности модели

---
## Результаты и обсуждение

Эксперименты показали эффективность модели в предсказании выживаемости пассажиров. На кросс-валидации последняя модель выдала точность 0.81, что является приемлемым результатом для данной задачи
