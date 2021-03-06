# VLAN-routing-between-virtual-local-networks
# Настроем базовые параметры для R1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_1.png)
![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_2.png)

# Настроем базовые параметры для S1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_3.png)

# Настроем базовые параметры для S2

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_4.png)

# Настроем базовые параметры для PCA-1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_5.png)

# Настроем базовые параметры для PCB-1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_6.png)

# Создаем сети VLAN и назначаем порты коммутатора
## Создаем сети VLAN на каммутаторах 
### S1
a) Создаем и называем необходимые VLAN на коммутаторе из таблицы 

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_7.png)
![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_9.png)

b) Настроем интерфейсы управления и шлюз по умолчанию используя информацию об IP-адресе в таблице адресации. 

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_8.png)

c) Скроим неиспользуемые порты коммутатора VLAN Parking_Lot

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_7.png)


# S2
a) Создаем и называем необходимые VLAN на коммутаторе из таблицы 
![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_10.png)
![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_11.png)

b) Настроем интерфейсы управления и шлюз по умолчанию используя информацию об IP-адресе в таблице адресации. 

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_12.png)

c) Скроим неиспользуемые порты коммутатора VLAN Parking_Lot
![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_10.png)

# Конфигурация магистрального канала стандарта 802.1Q между коммутаторами и маршрутизаторо.

S1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_14.png)

S2

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_15.png)

R1

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_13.png)

# Проверьте, работает ли маршрутизация между VLAN
а) Отправим эхо-запрос с PC-A на шлюз по умолчанию.

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_16.png)

Отправим эхо-запрос с PC-A на PC-B.

![](https://github.com/iGORnetwork/VLAN-routing-between-virtual-local-networks/blob/main/image/Screenshot_17.png)





