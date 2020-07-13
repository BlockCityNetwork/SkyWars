# SkyWars
SkyWars plugin for Nukkit

# API example:
Create custom class of ecomony handler

```java
public class MyEconomy extends CustomEconomy{
	public MyEconomy(SkyWars sw){ super(sw) }
	public void addMoney(Player p, int money){
		myPlugin.addMoney(p,money);
	}
	public int getMoney(Player p){
		return myPlugin.getMoney(p);
	}

```
and than, simple with 

```
SkyWars.getInstance().setEconomyHandler(myEconomy);
```
