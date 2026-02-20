# Soluções dos problemas do arquivo README.txt

---

#### 1. (B) Extract the "challenges.tar.gz" archive; you'll need its contents to solve some of the challenges.

```bash
tar -xf challenges.tar.gz
```

> *Anotações:* Como primeira tentativa tentei tar -x challenges.tar.gz e não funcionou <br>
> O comando tar é antigo e seu alvo eram fitas magnéticas, deve-se usar a flag f para indicar que é um arquivo específico


#### 2. (B) Change your working directory to the "challenges" directory that was created when you extracted "challenges.tar.gz"

```bash
cd challenges
```


#### 3. (B) List the contents of the "challenges" directory.

```bash
ls
```

> *Anotações:* A saída do comando foi <br>
> bunch_of_files  challenge_20  compile_me.c  greeting1.txt  greeting2.txt  hello_executable  people.csv  redirect  restricted.txt


#### 4. (B) Create a new directory named "foo".

```bash
mkdir foo
```


#### 5. (I) Create a new directory named "foo/bar/1/2/3"

```bash
mkdir -p foo/bar/1/2/3
```


#### 6. (B) Remove the directory "foo" and all of its contents

```bash
rm -fr foo
```

> *Anotações:* a flag ```r``` é usada para apagar subdiretórios, e a ```f``` para não pedir confirmação


#### 7. (B) Print the text "Hello World".

```bash
echo "Hello World"
```

#### 8. (B) Create a file named "hello.txt" that contains the text "Hello World".

```bash
echo "Hello World" > hello.txt
```

#### 9. (B) Create an empty file named "empty.txt"

```bash
touch empty.txt
```

#### 10. (B) Remove the file "empty.txt"

```bash
rm empty.txt
```

#### 11. (I) Find a second way to solve challenge 9.

```bash
> empty.txt
```

#### 12. (I) Find a third way to solve challenge 9.

```bash
echo -n > empty.txt
```

#### 13. (B) Copy "hello.txt" and name the copy "goodbye.txt".

```bash
cp hello.txt goodbye.txt
```

#### 14. (B) Rename "goodbye.txt" to "hello_copy.txt".

```bash
mv goodbye.txt hello_copy.txt
```

#### 15. (I) Prove that the contents of "hello.txt" and "hello_copy.txt" are identical.

```bash

```