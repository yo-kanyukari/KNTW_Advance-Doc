# 事前配布資料  

#### LAN とは  
同じ建物の中や、一つの家庭などの限定された範囲で接続できるネットワークのこと。
  
#### WAN とは  
遠く離れた場所と場所がつながったネットワーク。
簡単に言えば、LANとLANをつなぐ。
  
### ネットワークを構成するもの

- ルータや、L2ハブ、サーバなどの機器
- UTPケーブルや光ファイバなどのケーブル

#### 機器
今回使う機材にはGigabit Ethernet(GiGと書かれたものなど)のポートと Fast Ethernet(FEと書かれたものなど)のポートが存在する。  
Fastは上限が100Mbps、Gigabitは上限が1Gbpsで通信する。

- スイッチングハブ
    MACアドレスを見てパケットを流してくれる

[](computer_hub_loop_setsuzoku.png)

- ルータ  
    ネットワークの中継器。IPを見てパケットを流すなど、ルーティングプロトコルが扱える。

[](computer_wireless.png)

#### ケーブル
- 遠距離通信を支える光ファイバ。  
    高速通信を遠くまで敷設できる代わりに壊れやすい。  
  
- 近場のお供、UTPケーブル  
    通信の距離減衰が激しいが曲げたりできる。  
    　クロスケーブル：同種の危機(ルータとルータなど)の接続に使う  
    　ストレートケーブル：多種(ルータとPCなど)の接続に使う  
    しかし近年はautoMDI/MDI-Xがあるため、意識せずとも使うことができる  

### Ciscoルータの基本コマンド
今回のワークショップで直接触れるネットワーク機器は、CISCOのルータです。
CISCO機器はCLIで操作するため、基本的なコマンドを紹介しておきたいと思います。

#### モード

#### show 

#### interface


### ネットワークの技術
  
#### DHCP

#### NAT

#### ACL


#### VLAN


#### ルーティング
- IGP(説明)
    - RIP / RIP version2

    - OSPF

- EGP(説明)
    - BGP