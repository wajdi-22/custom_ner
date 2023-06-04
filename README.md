# custom_ner
the check points of  this model could be found here :
https://drive.google.com/drive/folders/1pLUUHdSHzvJmu5FKlBKx5VhLkYnDiwRn?usp=sharing

an exmple :
pipe("""A toy store has 30 stuffed animals, but only 20 fit on the shelves""")
output:
[{'entity_group': 'dalle',
  'score': 0.73263586,
  'word': 'toy store',
  'start': 2,
  'end': 11},
 {'entity_group': 'dalle',
  'score': 0.854738,
  'word': 'animals',
  'start': 27,
  'end': 34},
 {'entity_group': 'dalle',
  'score': 0.8931649,
  'word': 'shelves',
  'start': 59,
  'end': 66}]
sss
