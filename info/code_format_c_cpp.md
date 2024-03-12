# Как настроить форматирование для C C++

У меня возникали проблемки с форматированием кода в **Vs Code**. После их решения решил составить статью, которая поможет сэкономить несколько часов жизни.

<table>
<thead><tr><th>Bad</th><th>Good</th></tr></thead>
<tbody>
<tr><td>

```c
for (int i = 0; i < 10; i++)
{
    for (int j = 0; j < 10; j++)
    {
        // other code
    }
}
```

</td><td>

```c
for (int i = 0; i < 10; i++) {
    for (int j = 0; j < 10; j++) {
        // other code
    }
}
```

</td></tr>
</tbody></table>


## Небольшая настройка
Для настройки форматирования нужно выполнить следующие действия:
1) установить на свое устройство следующий фреймворк [LLVM Snapshot Builds](https://llvm.org/builds/)
2) установить следующее расширение для **Vs Code**, можно найти имени: **demiaochen.clang-format-indent-4**

**Примечание:** данная настройка работает на **Windows**, но не факт что будет работать на других ОС.