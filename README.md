<!-- HEADINGS-->

# my title h1

## my se title h2

### my title h3

#### my title h4

##### my title h5

###### my title h6

this is an _italic_ text

this is an **strong** text

este es un ~~tachado~~

- apple
  - apple 2
- orange

1. apple
   1. apple 2
2. orange
3. etc

[wikicax enlace](https://www.wikicax.com)

[wikicax enlace](https://www.wikicax.com "Custom Title")

> this is a quote

---

`console.log('hello world)`

```python

if mode == "dev":
    def run(updater):
        # funcion en la que vamos pidiendo a telegram si hemos recivido un mensaje
        updater.start_polling()
        print("BOT CARGADO")
        updater.idle()

elif mode == "prod":
    def run(updater):
        # Acceso HEROKU(producción), en este caso estamos a la escucha de mensajes
        PORT = int(os.environ.get("PORT", "8443"))
        HEROKU_APP_NAME = os.environ.get("HEROKU_APP_NAME")
        updater.start_webhook(listen="0.0.0.0", port=PORT, url_path=TOKEN)
        updater.bot.set_webhook(
            f"https://{HEROKU_APP_NAME}.herokuapp.com/{TOKEN}")
        updater.idle()

```

| Tables |  Are  |  Cool |
| ------ | :---: | ----: |
| sdasds | dsfdf | sddsd |
| sdasd  | sdsd  |    ew |

![visual studio code logo](https://mobilemancerblog.blob.core.windows.net/blog/2020/08/vs-code-logo-transp.png)

![visual studio code logo](vs-code.png "vs code logo")

<!--GITHUB MARKDOWN-->


- [x] Task 1
- [x] Task 1
- [ ] Task 1
- [x] Task 1

@MauroTory :smiley: :+1:
