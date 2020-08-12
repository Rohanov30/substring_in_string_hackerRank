# substring_in_string_hackerRank
str = input()
substr =input()

count = 0
for i in range(len(str) - len(substr) + 1):
    if string[i:i+len(substr)] == substr:
        count += 1
print(count)
