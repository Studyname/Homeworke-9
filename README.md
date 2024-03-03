# Homeworke-9
def remove_repeated_words(input_string):
result = re.sub(r'\b(\w+)\s+\1\b', r'\1', input_string)
return result

some_string = 'Напишите функцию функцию, которая будет будет будет будет удалять все все все все последовательные повторы слов из из из из заданной строки строки при помощи регулярных выражений'
print(remove_repeated_words(some_string))
