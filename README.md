# Slidown

**Português** | [English](#english) | [Español](#español)

<img alt="macOS" src="https://img.shields.io/badge/macOS-Tahoe%20(26)%2B-blue">
<img alt="Sem publicidade" src="https://img.shields.io/badge/publicidade-nenhuma-brightgreen">
<img alt="Baseado em" src="https://img.shields.io/badge/baseado%20em-yt--dlp-red">

---

## 🇧🇷 Português

**Slidown** é um app nativo de macOS pra baixar vídeos e áudios da forma mais simples possível — cola o link, aperta um botão, pronto. Feito com SwiftUI, pensado desde o início pra parecer (e se comportar) como qualquer app nativo do sistema: usa os componentes visuais padrão do macOS, respeita claro/escuro automaticamente, e não tenta reinventar nada que a Apple já resolveu bem.

Por baixo dos panos, o Slidown usa o **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — um projeto open source extremamente respeitado e mantido pela comunidade, responsável por entender e baixar conteúdo de centenas de sites diferentes. O Slidown não substitui o yt-dlp, ele só coloca uma interface amigável, nativa e em português por cima dele, cuidando de toda a parte chata (baixar o binário certo, manter atualizado, organizar a fila, detectar o site automaticamente) pra você não precisar tocar em terminal nenhum.

### Principais funcionalidades
- Interface 100% nativa, seguindo os padrões visuais do macOS
- Fila de downloads com modo simultâneo ou "modo lento" (evita bloqueios em sites sensíveis)
- Perfis por site, com detecção automática de qual configuração usar
- Acesso remoto pela mesma rede Wi-Fi — funciona de qualquer celular, tablet ou computador na rede, não só iPhone (cola o link de qualquer dispositivo, o Mac baixa)
- Atualização automática das ferramentas internas e do próprio app, sem precisar reinstalar manualmente
- Multilíngue: português, inglês, espanhol, francês, japonês e chinês

### Requisitos
- **macOS Tahoe (26) ou mais recente**
- Conexão com a internet (só pra baixar as ferramentas internas e os próprios vídeos)

### Instalação
1. Baixa o `.zip` mais recente na aba [Releases](../../releases)
2. Descompacta e arrasta o `Slidown.app` pra pasta Aplicativos

**Importante**: o Slidown é um projeto pessoal e **não é assinado pela Apple** (não passou pelo processo de notarização, que é pago). Por isso, na primeira vez que for abrir, o macOS vai bloquear com um aviso de "desenvolvedor não identificado". Pra liberar, escolha um dos dois caminhos:

- **Mais simples**: clica com o botão direito em cima do `Slidown.app` → **Abrir** → confirma no aviso que aparece (só precisa fazer isso uma vez)
- **Alternativa via Terminal**: cola esse comando (ajusta o caminho se instalou em outro lugar):
  ```
  xattr -cr /Applications/Slidown.app
  ```

Isso é uma característica normal de apps distribuídos fora da App Store, não um problema do Slidown em si.

### Sem publicidade, nunca
O Slidown não mostra anúncios, não vende dados, não tem nenhum tipo de rastreamento comercial embutido. É uma ferramenta pessoal, feita pra uso pessoal.

### Aviso legal
O Slidown é uma ferramenta de conveniência técnica. O uso responsável — respeitando direitos autorais e os termos de serviço de cada site — é de responsabilidade de quem usa o app. O projeto não hospeda, distribui nem tem qualquer relação com o conteúdo baixado através dele.

---

## English

**Slidown** is a native macOS app for downloading videos and audio as simply as possible — paste the link, hit a button, done. Built with SwiftUI from the ground up to look and behave like a proper native app: it uses standard macOS components, follows the system's light/dark appearance automatically, and doesn't try to reinvent anything Apple has already solved well.

Under the hood, Slidown is powered by **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — a highly respected, community-maintained open source project responsible for understanding and downloading content from hundreds of different sites. Slidown doesn't replace yt-dlp; it wraps it in a friendly, native, localized interface, handling all the tedious parts (fetching the right binary, keeping it updated, managing the queue, auto-detecting the site) so you never have to touch a terminal.

### Key features
- Fully native interface, following macOS design standards
- Download queue with simultaneous or "slow mode" (avoids rate limits on sensitive sites)
- Per-site profiles with automatic detection
- Remote access over the same Wi-Fi network — works from any phone, tablet, or computer on the network, not just iPhone (paste a link from any device, the Mac downloads it)
- Automatic updates for both the internal tools and the app itself, no manual reinstall needed
- Multilingual: Portuguese, English, Spanish, French, Japanese, and Chinese

### Requirements
- **macOS Tahoe (26) or later**
- Internet connection (only needed to fetch internal tools and the videos themselves)

### Installation
1. Download the latest `.zip` from the [Releases](../../releases) tab
2. Unzip it and drag `Slidown.app` into your Applications folder

**Important**: Slidown is a personal project and **is not signed by Apple** (it hasn't gone through Apple's paid notarization process). Because of this, the first time you open it, macOS will block it with an "unidentified developer" warning. To allow it, pick one of these:

- **Simplest**: right-click on `Slidown.app` → **Open** → confirm on the prompt that appears (only needed once)
- **Alternative via Terminal**: paste this command (adjust the path if you installed it elsewhere):
  ```
  xattr -cr /Applications/Slidown.app
  ```

This is standard behavior for apps distributed outside the App Store, not an issue specific to Slidown.

### No ads, ever
Slidown shows no ads, sells no data, and has no commercial tracking of any kind built in. It's a personal tool, built for personal use.

### Disclaimer
Slidown is a technical convenience tool. Responsible use — respecting copyright and each site's terms of service — is the responsibility of the person using the app. This project does not host, distribute, or have any relationship with the content downloaded through it.

---

## Español

**Slidown** es una app nativa de macOS para descargar videos y audio de la forma más simple posible — pega el enlace, presiona un botón, listo. Construida con SwiftUI desde el principio para verse y comportarse como cualquier app nativa del sistema: usa los componentes visuales estándar de macOS, respeta el modo claro/oscuro automáticamente, y no intenta reinventar nada que Apple ya haya resuelto bien.

Por debajo, Slidown funciona con **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — un proyecto de código abierto muy respetado y mantenido por la comunidad, responsable de entender y descargar contenido de cientos de sitios diferentes. Slidown no reemplaza a yt-dlp, solo le pone una interfaz amigable, nativa y localizada encima, encargándose de toda la parte tediosa (descargar el binario correcto, mantenerlo actualizado, organizar la cola, detectar el sitio automáticamente) para que nunca tengas que tocar una terminal.

### Funcionalidades principales
- Interfaz 100% nativa, siguiendo los estándares visuales de macOS
- Cola de descargas con modo simultáneo o "modo lento" (evita bloqueos en sitios sensibles)
- Perfiles por sitio, con detección automática de cuál configuración usar
- Acceso remoto por la misma red Wi-Fi — funciona desde cualquier celular, tablet o computadora en la red, no solo iPhone (pega el enlace desde cualquier dispositivo, la Mac lo descarga)
- Actualización automática de las herramientas internas y de la propia app, sin reinstalación manual
- Multilingüe: portugués, inglés, español, francés, japonés y chino

### Requisitos
- **macOS Tahoe (26) o posterior**
- Conexión a internet (solo para descargar las herramientas internas y los propios videos)

### Instalación
1. Descarga el `.zip` más reciente en la pestaña [Releases](../../releases)
2. Descomprímelo y arrastra `Slidown.app` a la carpeta Aplicaciones

**Importante**: Slidown es un proyecto personal y **no está firmado por Apple** (no pasó por el proceso de notarización, que es pago). Por eso, la primera vez que lo abras, macOS lo va a bloquear con un aviso de "desarrollador no identificado". Para permitirlo, elige uno de estos caminos:

- **Más simple**: clic derecho sobre `Slidown.app` → **Abrir** → confirma en el aviso que aparece (solo hace falta una vez)
- **Alternativa por Terminal**: pega este comando (ajusta la ruta si lo instalaste en otro lugar):
  ```
  xattr -cr /Applications/Slidown.app
  ```

Esto es un comportamiento normal de apps distribuidas fuera de la App Store, no un problema propio de Slidown.

### Sin publicidad, nunca
Slidown no muestra anuncios, no vende datos, no tiene ningún tipo de rastreo comercial integrado. Es una herramienta personal, hecha para uso personal.

### Aviso legal
Slidown es una herramienta de conveniencia técnica. El uso responsable —respetando derechos de autor y los términos de servicio de cada sitio— es responsabilidad de quien usa la app. El proyecto no aloja, distribuye ni tiene ninguna relación con el contenido descargado a través de él.
