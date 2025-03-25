# Uzbek Sentiment Intensity Dataset

This is an open-source Uzbek-language dataset labeled for **fine-grained sentiment analysis**.  
Each sentence is annotated with a sentiment category and its **intensity**, represented as both a descriptive label and a numeric score.

---

## 🔢 Sentiment Labels & Numeric Scores

| Label (Uzbek)            | Translation               | Numeric Score |
|--------------------------|---------------------------|----------------|
| juda kuchli salbiy       | very strongly negative     | -5             |
| kuchli salbiy            | strongly negative          | -4             |
| o‘rtacha salbiy          | moderately negative        | -3             |
| kam salbiy               | slightly negative          | -2             |
| juda kam salbiy          | very slightly negative     | -1             |
| neytral                  | neutral                    | 0              |
| juda kam ijobiy          | very slightly positive     | 1              |
| kam ijobiy               | slightly positive          | 2              |
| o‘rtacha ijobiy          | moderately positive        | 3              |
| kuchli ijobiy            | strongly positive          | 4              |
| juda kuchli ijobiy       | very strongly positive     | 5              |

---

## 📁 Dataset Format

The dataset is provided as a `.csv` file with the following columns:

| Column   | Description                                |
|----------|--------------------------------------------|
| `text`   | Sentence in Uzbek                          |
| `label`  | Sentiment label in Uzbek (e.g., "kam salbiy") |
| `score`  | Numeric sentiment score from -5 to 5       |

---

## 📊 Example

| text                           | label           | score |
|--------------------------------|------------------|--------|
| Juda g‘alati holat bo‘ldi.     | kuchli salbiy    | -4     |
| Yaxshi ishladingiz!            | kuchli ijobiy    | 4      |
| Mayli, baribir qiziq emas.     | juda kam salbiy  | -1     |
| Hali hech qanday fikrim yo‘q.  | neytral          | 0      |
| Ajoyib natija!                 | juda kuchli ijobiy | 5    |

---

## 🎯 Use Cases

This dataset is ideal for:

- Multi-class and fine-grained sentiment classification
- Sentiment regression modeling
- Uzbek language NLP tasks (TTS, STT, Chatbots, etc.)
- Cross-lingual and low-resource sentiment research
- Emotion-aware applications and analytics

---

## 🙋 Author

Created by [Gulshaxnoz](https://github.com/Gulshahnoz)  
Please cite or link to this repository if you use the dataset in your work.
