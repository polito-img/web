---
author: antonio
comments: false
#date: 2021-10-04 07:01:05+00:00
#layout: single
#link: theses/specific-proposals/thesis-creazione-di-unapplicazione-desktop-per-la-gestione-di-un-encoder-audio-video-utilizzando-software-open-source/
slug: thesis-creazione-di-unapplicazione-desktop-per-la-gestione-di-un-encoder-audio-video-utilizzando-software-open-source
title:
  "Thesis: Creazione di un’applicazione desktop per la gestione di un encoder
  audio/video utilizzando software open source"
wordpress_id: 3061
---

![]({{site.baseurl}}/res/2021/10/on-air.jpeg)

Nell’ambito della distribuzione dei contenuti audio e video sono presenti diversi moduli per implementare una catena di streaming con funzionalità avanzate. Lo scopo della Tesi è quindi volto alla creazione di un’applicazione desktop in grado di:

- poter creare dei flussi streaming audio o video tramite protocollo RTMP o [WebRTC](https://webrtc.org) nei codec richiesti (video H264 e audio HE-AAC);
- potersi interfacciare con un software di emissione audio o video per ricevere in ingresso il contenuto multimediale:
  - attraverso una scheda audio/video
  - attraverso un flusso passato tramite protocollo di trasporto UDP;
- oltre al flusso multimediale l’encoder si occuperà di inserire metadati tramite lettura da file o da specifica porta.

È possibile adottare i software open source [GStreamer](https://gstreamer.freedesktop.org) o [FFmpeg](https://ffmpeg.org) per effettuare il lavoro di encoding dei contenuti multimediali con i metadati. In questa libreria sono già presenti i moduli di gestione dei protocolli. La libreria è scritta in linguaggio C. Il linguaggio di programmazione per l’interazione con questa libreria e per la realizzazione dell’interfaccia grafica verrà concordato con il relatore.

Lo svolgimento dell’attività sarà presso Radiosa srl ( [www.radiosa.biz ](https://www.radiosa.biz)), azienda che opera nel settore media con soluzioni. Se interessato, puoi inviare il tuo CV e manifestazione di interesse a: antonio.servetti@polito.it.

Tags: multimedia, streaming, open source, distributed programming

Thesis type: applied research, software development
