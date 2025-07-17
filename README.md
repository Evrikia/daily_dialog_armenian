# DailyDialog Armenian (Seq2Seq Format)

This dataset is a **translated version** of the DailyDialog dataset, where all dialog lines have been translated into **Armenian**. It is structured in **Seq2Seq format**, which makes it suitable for training conversational AI models, machine translation models, or general-purpose sequence-to-sequence learning systems.

---

## 📚 Dataset Description

The original **DailyDialog** dataset consists of multi-turn dialogues on daily life topics. Each dialogue contains several utterances and is rich in emotional and communicative intent.

In this version:

- All utterances are translated into **Eastern Armenian**.
- Dialogues are flattened into **consecutive sentence pairs**.
- Format is compatible with **Seq2Seq** training, where:
  - `input` is a line from the dialogue.
  - `response` is the next consecutive line.

---

## 📁 File Format

The dataset is provided as a `.csv` file with the following structure:

| input | response |
|-------|--------|
| Բարեւ, ինչպե՞ս ես։ | Լավ եմ, շնորհակալ եմ։ Դու՞։ |
| Լավ եմ։ Ինչ նորություն կա։ | Ոչինչ առանձնահատուկ։ |

Each row represents a source-target sentence pair.

---

## 📊 Dataset Stats

- Total sentence pairs: ~76,000+
- Language: Armenian (Eastern)

---

## ✅ Use Cases

- Armenian chatbot training
- Dialogue modeling in low-resource languages
- Seq2Seq experiments
- Language model fine-tuning

---
