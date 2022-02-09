# Spigot Plugin Docs
> I'm just making this because Eclipse's Internal Web-Browser won't pass the SpigotMC DDoS check 


## Making a Basic Plugin with No Functionality in Eclipse

__Skip to step 3 if you already have a Java Project in Eclipse__

1. Open Eclipse
3. Select a folder you want to use as a Workplace
4. Click __Create a project...__ in the Project Explorer
5. Choose __Java > Java Project__
6. Click __Next__
7. Set the Project Name to your Plugin Name
8. Click __Finish__
9. Right Click your Project in the Project Explorer and choose __Build Path > Configure Build Path__
10. Click on the __Libraries__ Tab
11. Click __Add External JARs__
12. Select your Spigot JAR (You can find Spigot JARs [Here](https://getbukkit.org/download/spigot), just Download the Server Version you want your Plugin to be for)
13. Click __Open__ in the JAR selection screen
14. Click __Apply and Close__
15. Expand your Project in the Project Explorer by clicking the arrow next to it
16. Right Click on the __src__ entry and Click on __New > Package__
17. Setting Your Package Name
    - If you have a Website you should/can set your Package Name to this _You Website Domain_._Your Plugin Name_ with everything being lowercase
    - If you do not have a Website you should set your Package Name to something like this me._Your Name_._Your Plugin Name_ in all-lowecase
18. Right Click your Package and then Click __New > Class__
19. Set the Name to your Plugin Name in [Pascal Case](https://techterms.com/definition/pascalcase)
20. Change your Class to look like this:
```
package _Your Package Name_;
import org.bukkit.plugin.java.JavaPlugin;

public class _Your Class Name_ extends JavaPlugin {

}
```
21. Right Click on __src__ in entry in your Project Explorer
22. Click __New > File__ and set the Name to [plugin.yml](https://bukkit.fandom.com/wiki/Plugin_YAML)
23. Change you plugin.yml to look something like this:
```
name: _Your Plugin Name_
version: _Your Plugin Version_
description: _Your Plugin Description_
main: _Your Package Name_._Your Class Name_
```

And thats it, You just Created a Plugin with absolutely No Functionality
