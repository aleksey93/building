        
    <h1 class="title">Расчет количества газобетонных блоков для постройки дома</h1>
    <p>Калькулятор позволяет определить количество газобетонных блоков, необходимых для постройки дома.</p>

    <div id="blockRaschet">
        <div class="headPart" style="margin-top:10px;">1. Размеры жилого дома</div>
        <div class="clrboth"></div>

        <div class="block">
            <div class="label" style="height:50px;"><p>Периметр (м)</p></div>
            <div class="value" style="height:50px;"><p><input name="ctl00$ContentPlaceHolder1$tbLenght" type="text" value="0" id="ContentPlaceHolder1_tbLenght" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label" style="height:50px;"><p>Высота (м)</p></div>
            <div class="value" style="height:50px;"><p><input name="ctl00$ContentPlaceHolder1$tbBott" type="text" value="0" id="ContentPlaceHolder1_tbBott" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            

        <div class="headPart">2. Архитектурные особенности</div>
        <div class="clrboth"></div>
        <div class="messageText"><p><i>Если размеры дверей разные, то в поле <b>"Количество внешних дверей (шт)"</b> введите <b>"1"</b>, в поле <b>"Ширина одной двери (м)"</b> - сумму длин всех дверей, в поле <b>"Высота одной двери (м)"</b> - сумму высот всех дверей</i></p></div>
        <div class="clrboth"></div>
        <div class="block">
            <div class="label"><p>Количество внешних дверей (шт)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbKolvoDver" type="text" value="0" id="ContentPlaceHolder1_tbKolvoDver" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Ширина одной двери (м)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbWidthDver" type="text" value="0" id="ContentPlaceHolder1_tbWidthDver" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Высота одной двери (м)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbBottDver" type="text" value="0" id="ContentPlaceHolder1_tbBottDver" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            

        <div class="messageText"><p><i>Если размеры окон разные, то в поле <b>"Количество окон (шт)"</b> введите <b>"1"</b>, в поле <b>"Ширина одного окна (м)"</b> - сумму длин всех окон, в поле <b>"Высота одного окна (м)"</b> - сумму высот всех окон</i></p></div>
        <div class="clrboth"></div>
        <div class="block">
            <div class="label"><p>Количество окон (шт)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbKolvoOkon" type="text" value="0" id="ContentPlaceHolder1_tbKolvoOkon" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Ширина одного окна (м)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbWidthOkon" type="text" value="0" id="ContentPlaceHolder1_tbWidthOkon" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Высота одного окна (м)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbBottOkon" type="text" value="0" id="ContentPlaceHolder1_tbBottOkon" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            

        <div class="headPart">3. Кладка</div>
        <div class="clrboth"></div>
        <div class="block">

            <div class="label"><p>Цена блока за 1м<sup>3</sup> (грн.)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbPrice1" type="text" value="0" id="ContentPlaceHolder1_tbPrice1" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Вид блока</p></div>
            <div class="value"><p>
                <select name="ctl00$ContentPlaceHolder1$ddlBrick" id="ContentPlaceHolder1_ddlBrick" onchange="selectBlock(); return false;" style="width:240px;">
  <option value="24">500х250х200</option>
	<option value="13">500х250х300</option>
	<option value="14">550х250х200</option>
	<option value="15">550х250х300</option>
	<option value="7">600х250х100</option>
	<option value="2">600х250х150</option>
	<option value="4">600х250х200</option>
	<option value="9">600х250х250</option>
	<option value="10">600х250х300</option>
	<option value="11">600х250х350</option>
	<option value="12">600х250х400</option>
	<option value="23">600х250х80</option>
	<option value="5">600х500х100</option>
	<option value="6">625х250х100</option>
	<option value="21">625х250х150</option>
	<option value="18">625х250х200</option>
	<option value="19">625х250х250</option>
	<option value="16">625х250х300</option>
	<option value="20">625х250х350</option>
	<option value="17">625х250х400</option>
	<option value="22">625х500х100</option>

</select>
            </p></div>
            <div class="clrboth"></div>

            <div class="label"><p>Длина (мм)</p></div>
            <div class="value"><div id="ContentPlaceHolder1_widthDiv"><p>0</p></div></div>
            <div class="clrboth"></div>

            <div class="label"><p>Высота (мм)</p></div>
            <div class="value"><div id="ContentPlaceHolder1_heightDiv"><p>0</p></div></div>
            <div class="clrboth"></div>

            <div class="label"><p>Толщина (мм)</p></div>
            <div class="value"><div id="ContentPlaceHolder1_depthDiv"><p>0</p></div></div>
            <div class="clrboth"></div>

            <div class="label"><p>Цена клея за 1 мешок (грн.)</p></div>
            <div class="value"><p><input name="ctl00$ContentPlaceHolder1$tbPrice2" type="text" value="0" id="ContentPlaceHolder1_tbPrice2" style="width:150px;"></p></div>
            <div class="clrboth"></div>

            

        <div id="block">
            <div class="label2">
                <p>
                    <input type="submit" name="ctl00$ContentPlaceHolder1$tbRachet" value=" Рассчитать " onclick="return calc(); return false;" id="ContentPlaceHolder1_tbRachet">
                    <br><br>
                    <input id="butPrint" type="button" value="    Печать    " style="visibility:hidden;">
                </p>
             </div>
            <div class="messageRachet2"><div id="textRachet"></div></div>
            <div class="clrboth"></div>
        </div>

        <div class="clrboth"></div>
        <br>
    </div>

<input type="hidden" name="ctl00$ContentPlaceHolder1$hfParamClutch" id="ContentPlaceHolder1_hfParamClutch" value="24=500=250=200=0.025%13=500=250=300=0.0375%14=550=250=200=0.0275%15=550=250=300=0.04125%7=600=250=100=0.015%2=600=250=150=0.0225%4=600=250=200=0.03%9=600=250=250=0.0375%10=600=250=300=0.045%11=600=250=350=0.0525%12=600=250=400=0.06%23=600=250=80=0.012%5=600=500=100=0.03%6=625=250=100=0.015625%21=625=250=150=0.0234375%18=625=250=200=0.03125%19=625=250=250=0.0390625%16=625=250=300=0.046875%20=625=250=350=0.0546875%17=625=250=400=0.0625%22=625=500=100=0.03125%">

            </div>
        </div>
    </div>

    <div class="content2">
        <div class="mainContent2">
            <div class="contentMenu2">&nbsp;</div>
            <div class="contentText2">&nbsp;</div>
        </div>
    </div>
    
    
<script type="text/javascript"> 
<!--
    function selectBlock() {
        document.getElementById('butPrint').style.visibility = 'hidden';
        var ddlBrick = document.getElementById('ContentPlaceHolder1_ddlBrick');
        var brick = ddlBrick.options[ddlBrick.selectedIndex].value;

        var P1 = 0;
        var P2 = 0;
        var P3 = 0;
        var tmp = document.getElementById('ContentPlaceHolder1_hfParamClutch').value.split('%');
        for (var i = 0; i < tmp.length; i++) {
            var tmp2 = tmp[i].split('=');
            if (tmp2.length == 5 && tmp2[0] == brick) {
                P1 = tmp2[1];
                P2 = tmp2[2];
                P3 = tmp2[3];
            }
        }
        document.getElementById('ContentPlaceHolder1_widthDiv').innerHTML = "<p>" + P1 + "</p>";
        document.getElementById('ContentPlaceHolder1_heightDiv').innerHTML = "<p>" + P2 + "</p>";
        document.getElementById('ContentPlaceHolder1_depthDiv').innerHTML = "<p>" + P3 + "</p>";
    }


    function calc() {
        document.getElementById('butPrint').style.visibility = 'hidden';
        var N10 = 0;
        var N = 0;
        var V = 0;
        var K4 = document.getElementById('ContentPlaceHolder1_tbBott').value;
        var K2 = document.getElementById('ContentPlaceHolder1_tbLenght').value;
        var K7 = document.getElementById('ContentPlaceHolder1_tbKolvoDver').value;
        var K6 = document.getElementById('ContentPlaceHolder1_tbWidthDver').value;
        var K8 = document.getElementById('ContentPlaceHolder1_tbBottDver').value;
        var K9 = document.getElementById('ContentPlaceHolder1_tbKolvoOkon').value;
        var K10 = document.getElementById('ContentPlaceHolder1_tbWidthOkon').value;
        var K11 = document.getElementById('ContentPlaceHolder1_tbBottOkon').value;

        var price1 = document.getElementById('ContentPlaceHolder1_tbPrice1').value;
        var price2 = document.getElementById('ContentPlaceHolder1_tbPrice2').value;
        price1 = price1.replace(',', '.');
        price2 = price2.replace(',', '.');

        K4 = K4.replace(',', '.');
        K2 = K2.replace(',', '.');
        K6 = K6.replace(',', '.');
        K8 = K8.replace(',', '.');
        K10 = K10.replace(',', '.');
        K11 = K11.replace(',', '.');

        K7 = parseInt(K7);
        K9 = parseInt(K9);
        price1 = parseFloat(price1);
        price2 = parseFloat(price2);

        if (isNaN(K7) || isNaN(K9) || isNaN(parseFloat(K4)) || isNaN(parseFloat(K2)) || isNaN(parseFloat(K6)) || isNaN(parseFloat(K8)) || isNaN(parseFloat(K10)) || isNaN(parseFloat(K11)) || isNaN(parseFloat(price1)) || isNaN(parseFloat(price2))) {
            document.getElementById("textRachet").innerHTML = 'Ошибка при вводе значения!';
            return false;
        }

        var P1 = 0;
        var P2 = 0;
        var P3 = 0;
        var volume = 0;
        var Nam = '';

        var ddlBrick = document.getElementById('ContentPlaceHolder1_ddlBrick');
        var brick = ddlBrick.options[ddlBrick.selectedIndex].value;
        Nam = ddlBrick.options[ddlBrick.selectedIndex].text;

        var tmp = document.getElementById('ContentPlaceHolder1_hfParamClutch').value.split('%');
        for (var i = 0; i < tmp.length; i++) {
            var tmp2 = tmp[i].split('=');
            if (tmp2.length == 5 && tmp2[0] == brick) {
                P1 = tmp2[1];
                P2 = tmp2[2];
                P3 = tmp2[3];
                volume = tmp2[4];
            }
        }


        N10 = (parseFloat(P1) / 1000) * (parseFloat(P2) / 1000);
        N = (K2 * K4 - K6 * K7 * K8 - K9 * K10 * K11) / N10;
        V = N * volume;
        N = Math.round(N);
        V = Math.round(V);
        document.getElementById("textRachet").innerHTML = 'Расчетное количество материала формата "' + Nam + '" равно <b>' + N + '<\/b> штук, объем = <b>' + V + ' м<sup>3</sup></b>, на сумму <b>' + V * price1 + ' грн.</b>.<br/>Средний расход клея для кладки блоков 25кг (1 мешок) на 1м<sup>3</sup>, т.е. <b>' + V + ' мешков</b>, на сумму <b> ' + V * price2 + ' грн.</b></br>Расчеты не точны на 100%, поэтому материал надо брать с запасом.';

        
    }

   
    </script>


    
    </form>


</body></html>
