InetSim e Wireshark

In questo report si potrà vedere l'utilizzo del tool "InetSim e Wireshark"

Cos'è InetSim?

  InetSim è un tool oper source  che si può trovare già installato su Kali Linux. 
  INetSim è una suite software per la simulazione di servizi Internet comuni in un ambiente di laboratorio,
  ad esempio per l'analisi del comportamento della rete di campioni di malware sconosciuti.

INetSim supporta la simulazione dei seguenti servizi: HTTP, SMTP, POP3, DNS, FTP, NTP, TFTP, IRC, Ident, Finger, Ecc..

Cos'è Wireshark?
ha la capacità di catturare tutti i pacchetti transitanti da un adattatore Ethernet o Wi-Fi di un computer
e decodificarli in un “linguaggio” idoneo all'analisi di un sistemista o amministratore di rete.

Passaggi:
 1.Aprire la MV "kali"<br>
  2.Aprire il terminale e inviare il comando "InetSim"<br>
   3.Una volta lanciato il comando si aprirà il tool dove si potrà vedere la simulazione di servizi internet.<br>
    4.Aprire un secondo terminale e con il comando "Ping (ip server InetSim) vedere se le il client e il server comunichino.<br>
     5.Una volta che abbiamo constatato che le due macchine si vedino , apriremo Wireshark cosi da poter intercettare i paccheti .
     

