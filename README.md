# onlineclassbot
π‘ μ¨λΌμΈ ν΄λμ€μ© λ΄

![μ»€λ² μ¬μ§](https://raw.githubusercontent.com/cjaewon/onlineclassbot/main/media/cover.png)

## Features
- μκ°ν μλ¦Ό κΈ°λ₯

## How to Use
```sh
go run main.go
```
### μ€μ νμΌ
`.onlineclassbot.toml` νμΌμ ν΅ν΄μ λ΄μ μ€μ  ν  μ μμ΅λλ€.
```toml
[schedules] # μκ°ν
  [schedules."35 8 * * 1-5"]
    teacher = "λ΄μ ***"
    url = "https://us04web.zoom.us/j/abc123"

  [schedules."20 16 * * 1-5"]
    teacher = "λ΄μ ***"
    url = "https://us04web.zoom.us/j/abc123"

  # ..

[bot]
  token = "" # λμ€μ½λ λ΄ ν ν°
  notify_id = "" # μκ°νλ₯Ό λ³΄λΌ μ±λ id
```