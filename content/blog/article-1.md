# Títol de la web
title = "El meu Lloc Web Professional"

# URL de la web (domini base)
baseURL = "https://usuari.github.io/el-meu-hugo/"

# Tema utilitzat
theme = "ananke"

# Descripció i Metadades (SEO)
languageCode = "ca-es"
description = "Un lloc web creat amb Hugo per mostrar projectes personals i professionals."

[params]
  # Autor del lloc
  author = "Marc"
  subtitle = "Portafolis i Bloc de Sistemes"
  
  # Estructura del menú de navegació principal
  [menu]
    [[menu.main]]
      name = "Inici"
      url = "/"
      weight = 10
    [[menu.main]]
      name = "Projectes"
      url = "/projectes/"
      weight = 20
    [[menu.main]]
      name = "Sobre mi"
      url = "/about/"
      weight = 30
    [[menu.main]]
      name = "Contacte"
      url = "/contact/"
      weight = 40
