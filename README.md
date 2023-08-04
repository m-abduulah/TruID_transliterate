# TruID_transliterate
A python script use to transliterate addresses of Pakistan from urdu to roman urdu

Based on the library of AI4bharat
we declare the urdu-roman dictionary of all districts/populated cities (200) in pakistan
along with it we also declare the common phrases used in address such as gali, stree, block
break down the address into words, if word is found in lookup dictionary it is fetched from there, if not the xlit model of ai4bharat predicts the word
