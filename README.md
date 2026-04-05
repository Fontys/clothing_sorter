# 👗 Clothing Sorter
This notebook shows how to use transfer learning to fine tune an existing image classification model on a new dataset. In this case we have taken the [Clothing Dataset](https://github.com/alexeygrigorev/clothing-dataset) by Alexey Grigorev, which contains 10 classes of different attire.

<img src="https://raw.githubusercontent.com/bshtmichielsen/clothing_sorter/refs/heads/main/BANNER.jpg" />

*Image by Stable Diffusion: a machine sorting clothing items and attire, colourful, funny*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. This repo belongs to a five part course:&nbsp;&nbsp;&nbsp; 🏠&nbsp;[House&nbsp;Price&nbsp;Predictor](https://github.com/Fontys/house_price_predictor)&nbsp;&nbsp;&nbsp; 🐏&nbsp;[Animal&nbsp;Sound&nbsp;Identifier](https://github.com/Fontys/animal_sound_identifier)&nbsp; &nbsp;👗&nbsp;[Clothing&nbsp;Sorter](https://github.com/Fontys/clothing_sorter)&nbsp;&nbsp;&nbsp; 🌼&nbsp;[Wildflower&nbsp;Finder](https://github.com/Fontys/wildflower_finder)&nbsp;&nbsp;&nbsp; 💬&nbsp;[Expert&nbsp;Chat](https://github.com/Fontys/expert_chat)&nbsp; Feel free to learn from the other parts too!

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - Understand the principle ideas around [transfer learning](https://www.geeksforgeeks.org/machine-learning/ml-introduction-to-transfer-learning/).

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
- Working with image files as data for machine learning
- Using transfer learning rather than building neural network layers yourself.
- Freezing and unfreezing layers.

## 🤔 Considerations for improvement
The following is a list of considerations for improvement or for your own project.

- Note that the test is a bit unfair because we do not ensure that the test set has an equal number of images per class.
- Given that this notebook uses transfer learning, it makes sense to freeze all layers at first. However, unfreezing them probably gives better outcomes. Can you measure the difference?
- Outputting all 160 test items as images is nice because it gives a clear overview, however, when the test set gets larger, this quickly get impractical. It may be worthwhile to select only the interesting cases. Can you update the code?
- Adding a Confusion Matrix could be a great idea.

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!

> Michielsen, Bas S.H.T. (2025) "Clothing Sorter" GitHub: https://github.com/Fontys/clothing_sorter
