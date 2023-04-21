# split text into words and count the number of words in each row
word_counts = df['text'].str.split().str.len()

# filter the dataframe to remove rows with only one word
df = df[word_counts > 1]
