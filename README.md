# 🌍 Эко-помощник по сортировке мусора

![Демо](<img width="1442" height="821" alt="Снимок экрана 2026-02-16 в 19 42 43" src="https://github.com/user-attachments/assets/8395ac9a-eb95-4c00-8a12-235965330e68" />)

Нейросеть для классификации отходов на базе модели Trash-Net. Определяет тип мусора (пластик, стекло, бумага, металл и др.) и даёт рекомендации по переработке.

##  Как использовать в Colab
Все супер просто:
1. Открой [ноутбук в Colab]([https://colab.research.google.com/github/твой-юзернейм/eco-waste-classifier/blob/main/название_файла.ipynb](https://colab.research.google.com/drive/1oNGS_ev2eS8jkNueKzBJIfUx0IFwxK7A?usp=sharing))
2. Запусти первую ячейку с установкой библиотек!
3. Загрузи фото мусора , вставь ссылку или загрузи фото через веб-камеру! (кнопки взину сайта помогут чтобы не искать картинку и ссылку)
4. Получи результат с рекомендацией!!!

## мозги модели

- Модель: `prithivMLmods/Trash-Net`
- Датасет: TrashNet
- Точность: ~96%

## Зависимости

- transformers
- gradio
- pillow
- requests
