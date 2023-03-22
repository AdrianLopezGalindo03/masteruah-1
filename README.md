1. git clone https://github.com/miguelonvaa/masteruah
2. git add 1.txt
3. git commit -m "Creamos el fichero 1.txt"
4. git tag v0.1
5. git push --tags
6. git branch v0.2
7. git checkout v0.2
8. echo "contenido del fichero 2" > 2.txt
9. git add 2.txt
10. git commit -m "AÃ±adir fichero 2.txt a la rama v0.2"
11. git push -u origin v0.2
12. git checkout main
13. git merge v0.2
14. echo "Hola" > 1.txt
15. git add 1.txt
16. git commit -m " Agregado hola en fichero 1.txt en la rama main"
17. git checkout v0.2
18. echo "Adios" > 1.txt
19. git add 1.txt
20. git commit -m "Agregado adios en fichero 1.txt en la rama v0.2"
21. git checkout main
22. git merge v0.2
23. git branch --merge
24. git branch --no-merge
25. git status
26. vim 1.txt
27. git add 1.txt
28. git commit -m "resulto conflito fichero 1.txt"
29. git status
30. git tag v0.2
31. git branch -D v0.2
32. cd ~/.ssh
33. ls
34. ssh-keygen
35. cat clave.pub
