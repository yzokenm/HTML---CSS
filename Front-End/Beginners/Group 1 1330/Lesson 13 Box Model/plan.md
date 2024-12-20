Ushbu <div> elementining umumiy kengligi 350px va umumiy balandligi 80px boʻladi:
div {
    width: 320px;
    height: 50px;
    padding: 10px;
    border: 5px solid gray;
    margin: 0;
}

Hisob kitob:
320px (width of content area) => kontent maydonining kengligi
+ 20px (left padding + right padding) => chap va o'ng padding(to'ldirish)
+ 10px (left border + right border) => chap va o'ng chegara
= 350px (total width) => to'liq kengligi 

  50px (height of content area) kontent maydining balandligi
+ 20px (top padding + bottom padding) => tepa va pas padding(to'ldirish)
+ 10px (top border + bottom border) => tepa va pas chegara
= 80px (total height) => to'liq balandlik



Elementning umumiy kengligi(total width) quyidagicha hisoblanishi kerak:

Elementning umumiy kengligi = kenglik(width) + chap to'ldirish(left padding) + o'ng to'ldirish(right padding) + chap chegara(border left) + o'ng chegara(border right)

Elementning umumiy balandligini(total height) quyidagicha hisoblash kerak:

Jami element balandligi = balandlik(height) + yuqori to'ldirish(top padding) + pastki to'ldirish(bottom padding) + yuqori chegara(border top) + pastki chegara(border bottom)