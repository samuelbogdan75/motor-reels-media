# motor-reels-media

Alojamiento público de los vídeos del canal para que Metricool los descargue.

- Rama `videos`: una carpeta por día (`AAAA-MM-DD/video.mp4`). Se reescribe con un commit huérfano en cada run: no acumula historial.
- La gestiona la rutina diaria de `motor-reels` (`pipeline/media_push.py`). No subas nada a mano.
