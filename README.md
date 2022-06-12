# Telegram Misinformation Data about the 2022 Ukraine-Russia conflict

The data is split into three folders: train, test, and validation. Each folder has a data frame with a `text` column, and a `label` column, among others.
- Text is the original language text of a Telegram post. 
- Lablel is the label given by us for each text based on the channel the text appeared in, e.g. all posts made by a Russian state propangada channel like Tass Agency are label as Russian Propaganda.
  - It can be `0` (Russian Misinformation), `1` (Russian Propaganda) or `2` (Real News). 
