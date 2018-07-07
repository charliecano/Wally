# Wally
Change OSX Wallpaper Mojave (Morning|Afternoon|Evening)

Here is apple script to change wallpaper on macosx based on time of day (Morning\Afternoon\Evening)
You could put desired pictures in folders:

Create folders

bash: 
mkdir -pv '$HOME/Pictures/Wallpapers/Morning', '$HOME/Pictures/Wallpapers/Afternoon', '$HOME/Pictures/Wallpapers/Evening'

Run script : 
"osascript ~/$HOME/Pictures/Wallpapers/wallpaper.scpt"

Create cron task in terminal:
crontab -e
Copy without quotes: "30 * * * * osascript $HOME/Pictures/Wallpapers/wallpaper.scpt" #Run script every 30 min.

<a href=https://www.computerhope.com/unix/ucrontab.htm>Crontab Help</a>

Maybe better solution to use GUI Cron app:
<a href=https://www.macupdate.com/app/mac/7486/cronnix/> Cronnix </a>
