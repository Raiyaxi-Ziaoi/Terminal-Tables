<img src="https://i.imgur.com/lRzzpEU.png"></img>

# Desk

<div align="center"><h2><br/><br/>
 A library for tables in the terminal in Java<br/><br/>Made by Raiyaxi Ziaoi
</h2></div>
<br>

Usage: <br/>

```java
Desk desk = new Desk();
desk.print();
```

<br/>
This will print out a table with dummy info. You can use the manual constructor like:<br>

```java
Desk desk = new Desk("-", "+", "|", true, false, "none");
```

to allow for more customisation.
<br/><br/>
There are also templates such as 'time', 'list' and 'data'

```java
Desk desk = new Desk("-", "+", "|", true, false, "time");
```

<br/>
They provide a scaffolding for your table based on your specific needs.
