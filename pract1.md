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
