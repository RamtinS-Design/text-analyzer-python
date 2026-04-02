from collections import Counter


question = input('Enter the word or the sentence: ')
choice = input('Choose (words / characters / frequent): ')


def count_words(question):
    words = question.split()
    return len(words)

def count_characters(question):
    characters = question.lower()
    return len(characters)

def most_frequent(question):
    question = question.split()
    return Counter(question).most_common(1)[0][0]

if choice == 'words':
    print('Number of words: ', count_words(question))

elif choice == 'characters':
    print('Number of characters: ', count_characters(question))

elif choice == 'frequent':
    print('Most frequent word: ', most_frequent(question))

else:
    print('Invalid Option')






