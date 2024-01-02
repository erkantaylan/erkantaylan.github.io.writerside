# This should be the landing page 

## Writerside is so far fantastic

I like fast output. Let's test this on GitHub personal page. 

```mermaid
sequenceDiagram
    actor Eczaci
    Eczaci->>IlacTarif: ilac
    IlacTarif-)Sunucu: 1x2 Gunde 3
    Sunucu-)IlacTarif: {DosageWarningCode: 1}
    IlacTarif-)DosageWarningSunucu:getWarning/{warning id}
    DosageWarningSunucu-)IlacTarif: {"code" : 1,"message":"dikkat dikkat uyarı"}
    IlacTarif-)Eczaci:Doz Bilgisi Doğrulama
    
```