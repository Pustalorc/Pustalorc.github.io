<h1>Public Programs</h1>

[Unturned Server Manager](https://persiafighter.github.io/UnturnedServerManager/) [![Build status](https://ci.appveyor.com/api/projects/status/bocigasg3gog25rg/branch/master?svg=true)](https://ci.appveyor.com/project/persiafighter/unturnedservermanager/branch/master)

[Rocket Rules](https://persiafighter.github.io/Rocket-Rules/) [![Build status](https://ci.appveyor.com/api/projects/status/pb6sp9f67e4dj9is?svg=true)](https://ci.appveyor.com/project/persiafighter/rocket-rules)

[Fake Gambling - Crash](https://github.com/persiafighter/FakeGambling-Crash) [![Build status](https://ci.appveyor.com/api/projects/status/lnc18aoqi6s50u2w?svg=true)](https://ci.appveyor.com/project/persiafighter/fakegambling-crash)

<h1>Programs in developement</h1>

Unturned Server Manager V3.0.0.0 - Time Left: <div id="countbox"></div><SCRIPT TYPE="text/javascript" LANGUAGE="JavaScript"><!--

dateFuture = new Date(2017,0,1,17,00,00);

function GetCount(){

        dateNow = new Date();                                                                        //grab current date
        amount = dateFuture.getTime() - dateNow.getTime();                //calc milliseconds between dates
        delete dateNow;

        // time is already past
        if(amount < 0){
                document.getElementById('countbox').innerHTML="Now!";
        }
        // date is still good
        else{
                days=0;hours=0;mins=0;secs=0;out="";

                amount = Math.floor(amount/1000);//kill the "milliseconds" so just secs

                days=Math.floor(amount/86400);//days
                amount=amount%86400;

                hours=Math.floor(amount/3600);//hours
                amount=amount%3600;

                mins=Math.floor(amount/60);//minutes
                amount=amount%60;

                secs=Math.floor(amount);//seconds

                if(days != 0){out += days +" day"+((days!=1)?"s":"")+", ";}
                if(days != 0 || hours != 0){out += hours +" hour"+((hours!=1)?"s":"")+", ";}
                if(days != 0 || hours != 0 || mins != 0){out += mins +" minute"+((mins!=1)?"s":"")+", ";}
                out += secs +" seconds";
                document.getElementById('countbox').innerHTML=out;

                setTimeout("GetCount()", 1000);
        }
}

window.onload=function(){GetCount();}//call when everything has loaded

//-->
</script>

Rocket Remote - A plugin that works like an API for external programs to hook up with the unturned servers.

Rocket Trading - A plugin that allows players to trade items with eachother without having to be near themselves.

Rocket Jobs - A roleplay plugin that allows players to get a job without the need of admins.

<h1>Custom Programs/Plugins</h1>

Reputation Loadout - A plugin that will give a loadout/kit to a player after respawn when the player has a specific reputation. - Reserved to '[Ikatzuki](http://steamcommunity.com/id/Ikatzuki1/)'

<h1>Donate</h1>

[Steam](https://steamcommunity.com/tradeoffer/new/?partner=171975117&token=nPB07kkc)
