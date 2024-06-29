# My Personal Curriculum vitae

## 1. Name: Ramil Kayumov

### 2. Contacts:
* tg - @RamilTe
* email - hfvbkmr@gmail.com

### 3. About me:
* **Aim in Life -** To keep discovering new things and always have room to grow and evolve. Here’s what drives my interests
    > BJJ 🥋 - Where getting tangled up means progress

    > VIM ⌨️  - Spending hours tweaking configurations to save a few seconds of typing

    > Factorio 🎮 - Turning chaos into perfectly synchronized factory lines

### 4. Skills:
* HTML, CSS
* JavaScript
* PHP
* MySQL
* Postman
* DevTools (monitoring and modifying API responses)
* K6 (simple load tests)
* Docker

### 5. **Code Examples:**
* Here's a Docker Compose configuration to run the same PHP script in two different PHP versions (5.6 and 7.0):

```yaml
version: "3"

services:
  php56:
    image: php:5.6-cli
    container_name: php56
    working_dir: /src/counter/
    command: php counter.php
    volumes: 
      - "C:/path/to/workspace/counter:/src/counter/:ro"

  php70:
    image: php:7.0-cli
    container_name: php70
    working_dir: /src/counter/
    command: php counter.php
    volumes: 
      - "C:/path/to/workspace/counter:/src/counter/:ro"

```

## 6. **Work Experience:**
* **Company -** Hero Study 🦸
    + **Position -** QA
    + **Duration -** June 2022 / Present

## 7. Education
* Constantly learning through
    + Courses such as CS50, freeCodeCamp, Hexlet
    + Reading documentation of the technologies I am interested in
    + Practicing on Codewars

## 8. Languages
* Russian (Native)
* English (Upper-Intermediate)

