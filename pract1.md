# Задание 1
```
cat /etc/passwd | grep -o -E '^\w+' | sort
```
![](num1res.png)

# Задание 2
```
cat /etc/protocols | awk '{print $2, $1}' | sort -nr | head -5
```
![](num2res.png)

# Задание 3
```
line = input()
print("+" + "-" * (len(line) + 2) + "+")
print("| " + line + " |")
print("+" + "-" * (len(line) + 2) + "+")
```
![](num3res.png)

# Задание 4
```
cat hello.c | grep -o -E '\b[a-zA-Z_][a-zA-Z_0-9]*\b' | sort -u
```
![](num4res.png)

# Задание 5
```
file=$1
chmod 755 "./$file"
sudo cp "$file" /usr/local/bin/
```
![](num5res.png)
