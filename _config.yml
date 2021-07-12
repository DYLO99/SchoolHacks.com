
<!DOCTYPE html>

<html>

    <head>

        <meta charset="utf-8">
<!--
Created using JS Bin
http://jsbin.com

Copyright (c) 2021 by Vekdrop (http://jsbin.com/yizohafewo/1/edit)


-->
<meta name="robots" content="noindex">

    </head>

    <body>

        <h2>Drop Knife or Gloves</h2>
    
        <p>
            <label for="name">Steam name</label>
            <input id="name" type="text" value="Player">

        </p>

        <p>
            <label for="item">Item name</label>
            <input id="item" type="text" value="Karambit">
            
        </p>

        <p>
            <input id="starred" type="checkbox" value="Player" checked>
            <label for="starred">Knife or gloves?</label>
            
        </p>

        <p>
            <label for="paintkit">Weapon color</label>
            <input id="paintkit" type="text" value="Lore">
            
        </p>

        <p>
            <input id="stattrak" type="checkbox" value="Player" checked>
            <label for="stattrak">StatTrack&trade;?</label>
            
        </p>

        <p>
            <label for="rarity">Rarity</label>

            <select id="rarity">

                <option value="0x0F" selected>red</option>
                <option value="0x0E">pink</option>
                <option value="0x0C">blue</option>

            </select>
            
        </p>

        <input id="dummyinput" style="position:absolute;left:-100%" type="text">
        <button onclick="copy()">Copy✔</button>

        <script>

            var copy = () =>
            {
                let name = document.getElementById("name").value;
                let item = document.getElementById("item").value;
                let starred = document.getElementById("starred").checked ? "★" : "";
                let paintkit = document.getElementById("paintkit").value;
                let stattrak = document.getElementById("stattrak").checked ? " StatTrak™" : "";
                let rarity = String.fromCharCode(eval(document.getElementById("rarity").value));

                let input = document.getElementById("dummyinput");
                input.value = `playerradio Radio.WePlanted "\u2028\x03\x03${name} \x01has opened a container and found: ${rarity}${starred}${stattrak} ${item} | ${paintkit}"`;
                input.select();
                input.setSelectionRange(0, input.value.length)
                document.execCommand("copy");
            };

        </script>

    <script src="https://static.jsbin.com/js/render/edit.js?4.1.8"></script>
<script>jsbinShowEdit && jsbinShowEdit({"static":"https://static.jsbin.com","root":"https://jsbin.com"});</script>
<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

ga('create', 'UA-1656750-34', 'auto');
ga('require', 'linkid', 'linkid.js');
ga('require', 'displayfeatures');
ga('send', 'pageview');

</script>

</body>

</html>
