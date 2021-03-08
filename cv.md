# Pavel Homal

## Contacts

Discord: naXa777#3672
Phone: +48 798 907 ***

## About me

A freelancer software developer. Upwork Top Rated Plus talent.

Fullstack Engineer at [Found.ee](https://found.ee/super).

## Technologies stack

* Front-end
    * HTML + CSS + JS
    * TypeScript
    * ReactJS
    * Android
    * Swagger codegen
    * yarn
* Back-end
    * SQL
    * Java
    * Kotlin
    * Spring Framework
    * Liquibase
    * FreeMarker
    * Swagger UI
    * Gradle and Maven
* Other
    * Markdown
    * XML
    * JSON
    * YAML
    * Git

## Code sample

See [task description](https://www.codewars.com/kata/58f5c63f1e26ecda7e000029).

```kt
fun wave(str: String): List<String> {
    val waveFrames = mutableListOf<String>()
    val chars = str.toCharArray()
    for (i in chars.indices) {
        if (chars[i] == ' ') continue
        chars[i] = chars[i].toUpperCase()
        waveFrames.add(String(chars))
        chars[i] = chars[i].toLowerCase()
    }
    return waveFrames.toList()
}
```
