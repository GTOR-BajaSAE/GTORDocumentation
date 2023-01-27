[![](https://mermaid.ink/img/pako:eNqFVG1v2jAQ_iunfC4rSdRpotI-hNKKrahRQ9VJph88cgsRjhM5TgHV_e-7OAkUChQJOJ_vee7Fd_fmzPMYnYGTKF4sYHpzPZPQfp6iUFTJhAtko7VGJbkgHdRKGMsX6PV-wnDBVYKKUDtcq2O3lRAbstQoRJqg1BBWokR4xIKnqjNreMydQpQQrVI9XxhwvVdGXxhyBQHX5HzzsuejvrS4B8Vlgltg6PYZfSHKuNIddOvq-muCsXxFRSAWjKLp6Ddc9fsrCPMVqu3VfiS1t5oo4ILLObqsFTqn4H50e2DtfbL29tk7nxYURi67WvttOJFWaXHG2jxFAZkqbejVAuat6z__W9_qyoMkIrfBeBCqXCadi6ooxMZ00fpsihJVsoGDqE-QBYLPl_DMhaAfeo7VJdyPbgw88jjNXfZ97TbiNvkeWMhewU6QtSwe89feEZYKj8Zknhepxo8sNtGAyyVrUq7FEtyefyInf69AQ_5XoGkn5Razo7PyUOkzhN4xwkkqVrxaIrKJ611O3B87TZfmwQve53mJY41ZyawIVm6HK0rFq80tMS28nQzWnLaDQhYfi78jbXjCYWDgPk0W-o5rrFvKHqA-AV2ewzbvx2VM8x8b-FVlBSqbblkTNecm__Jrnu4Z2nrZ4o1lUWnWzSrJze05sqYdWjJD_U7FIFnjXOfKNqhVwVb3cpqLVg51VRNeV0_q-D9Tv2_qRdaV_NNecy6cDFXG05j28FvtYOboBWY4cwYkxlwtZ85MvpMdr3QebeTcGWhV4YVTFTGV_ibltL4zZ_CP0369cDBOKdRJs9jtfn__D0ur3bE?type=png)](https://mermaid.live/edit#pako:eNqFVG1v2jAQ_iunfC4rSdRpotI-hNKKrahRQ9VJph88cgsRjhM5TgHV_e-7OAkUChQJOJ_vee7Fd_fmzPMYnYGTKF4sYHpzPZPQfp6iUFTJhAtko7VGJbkgHdRKGMsX6PV-wnDBVYKKUDtcq2O3lRAbstQoRJqg1BBWokR4xIKnqjNreMydQpQQrVI9XxhwvVdGXxhyBQHX5HzzsuejvrS4B8Vlgltg6PYZfSHKuNIddOvq-muCsXxFRSAWjKLp6Ddc9fsrCPMVqu3VfiS1t5oo4ILLObqsFTqn4H50e2DtfbL29tk7nxYURi67WvttOJFWaXHG2jxFAZkqbejVAuat6z__W9_qyoMkIrfBeBCqXCadi6ooxMZ00fpsihJVsoGDqE-QBYLPl_DMhaAfeo7VJdyPbgw88jjNXfZ97TbiNvkeWMhewU6QtSwe89feEZYKj8Zknhepxo8sNtGAyyVrUq7FEtyefyInf69AQ_5XoGkn5Razo7PyUOkzhN4xwkkqVrxaIrKJ611O3B87TZfmwQve53mJY41ZyawIVm6HK0rFq80tMS28nQzWnLaDQhYfi78jbXjCYWDgPk0W-o5rrFvKHqA-AV2ewzbvx2VM8x8b-FVlBSqbblkTNecm__Jrnu4Z2nrZ4o1lUWnWzSrJze05sqYdWjJD_U7FIFnjXOfKNqhVwVb3cpqLVg51VRNeV0_q-D9Tv2_qRdaV_NNecy6cDFXG05j28FvtYOboBWY4cwYkxlwtZ85MvpMdr3QebeTcGWhV4YVTFTGV_ibltL4zZ_CP0369cDBOKdRJs9jtfn__D0ur3bE)

```mermaid
    graph TD;
        USPlugMale[External US Plug In] --> Charger;

        Charger[Fully Intelligent Pulse Repair Charger] --> |Green Switch| 12v[12v Car Battery];

        12v --> |Orange Switch| P10[P10 Smart Battery Charger];
        12v --> |Orange Switch| Inverter[BESTEK 500w Power Inverter];

        P10 --> Balance1[Balance Charger 1];
        P10 --> Balance2[Balance Charger 2];

        Inverter --> PS1[5x3 Power Strip];

        Inverter --> |USB Port| USB[2x USB3.0 Ports];

        PS1 --> |2 Prong Power Supply| Balance3[Tenergy Balance Charger];

        PS1 --> |Black Wall Wart w/ LED| Radio1[6x1 Radio Charger - Black];
        PS1 --> |Black Wall Wart| Radio2[3x2 Radio Charger - Blue];

        PS1 -->|White Wall Wart| PowerBank[Power Banks 1-3];

        PS1 --> |3 Prong Power Cable| USPlugFemale[External US Plug Out 1-3];

        PS1 --> |2 Prong Power Cable| Milwaukee[M12/M18 Milwaukee Chargers];

        LooseItems[Loose Items] --> |Silver Bag| ChargeBattery[Charge Battery Bag];
        LooseItems --> |PCB| LightGate[2x Light Gate PCB];
        LooseItems --> |Black and Red| JumperCables[2x Jumper Cables];
        LooseItems --> |Black 3 Prong Cable| PowerInput[Power Input Cable];
        LooseItems --> |White 3 Prong| SurgeProtector[6x1 Surge Protector]
        LooseItems --> |Small Black Battery w/ XT30| CarBattery[12v Car Battery];
```
