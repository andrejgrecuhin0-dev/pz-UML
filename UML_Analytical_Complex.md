# UML Діаграми — Аналітичний комплекс відкритих джерел

## 1. Use Case Діаграма

### Опис
Діаграма варіантів використання показує взаємодію акторів (Аналітик, Адміністратор) з функціями системи.

### XML для draw.io

```xml
<mxGraphModel dx="1422" dy="762" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1169" pageHeight="827" math="0" shadow="0">
  <root>
    <mxCell id="0"/>
    <mxCell id="1" parent="0"/>
    <mxCell id="2" value="ІС «Аналітичний комплекс відкритих джерел»" style="ellipse;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=13;fontStyle=1;verticalAlign=top;" vertex="1" parent="1">
      <mxGeometry x="220" y="40" width="560" height="720" as="geometry"/>
    </mxCell>
    <mxCell id="3" value="Авторизація" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="100" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="4" value="Налаштування джерел" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="190" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="5" value="Запуск збору даних" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="280" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="6" value="Моніторинг збору" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="370" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="7" value="Фільтрація даних" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="460" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="8" value="Аналіз та візуалізація" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="550" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="9" value="Експорт результатів" style="ellipse;whiteSpace=wrap;html=1;fillColor=#ffffc0;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="310" y="640" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="10" value="Управління користувачами" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="530" y="190" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="11" value="Налаштування системи" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="530" y="280" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="12" value="Журнали подій" style="ellipse;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1">
      <mxGeometry x="530" y="370" width="180" height="50" as="geometry"/>
    </mxCell>
    <mxCell id="13" value="Аналітик" style="shape=umlActor;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#000000;fontSize=12;verticalLabelPosition=bottom;verticalAlign=top;" vertex="1" parent="1">
      <mxGeometry x="80" y="370" width="40" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="14" value="Адміністратор" style="shape=umlActor;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#000000;fontSize=12;verticalLabelPosition=bottom;verticalAlign=top;" vertex="1" parent="1">
      <mxGeometry x="880" y="280" width="40" height="60" as="geometry"/>
    </mxCell>
    <mxCell id="15" edge="1" source="13" target="3" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="16" edge="1" source="13" target="4" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="17" edge="1" source="13" target="5" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="18" edge="1" source="13" target="6" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="19" edge="1" source="13" target="7" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="20" edge="1" source="13" target="8" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="21" edge="1" source="13" target="9" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="22" edge="1" source="14" target="3" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="23" edge="1" source="14" target="10" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="24" edge="1" source="14" target="11" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="25" edge="1" source="14" target="12" parent="1" style="html=1;endArrow=none;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="26" value="&lt;&lt;include&gt;&gt;" style="dashed=1;endArrow=open;endFill=0;fontSize=11;html=1;" edge="1" source="5" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="27" value="&lt;&lt;include&gt;&gt;" style="dashed=1;endArrow=open;endFill=0;fontSize=11;html=1;" edge="1" source="8" target="7" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="28" value="&lt;&lt;extend&gt;&gt;" style="dashed=1;endArrow=open;endFill=0;fontSize=11;html=1;" edge="1" source="9" target="8" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
  </root>
</mxGraphModel>
```

---

## 2. Sequence Діаграма

### Опис
Діаграма послідовності показує покроковий порядок взаємодії між компонентами системи при виконанні сценарію збору, обробки та аналізу даних.

### XML для draw.io

```xml
<mxGraphModel dx="1422" dy="762" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1169" pageHeight="827" math="0" shadow="0">
  <root>
    <mxCell id="0"/><mxCell id="1" parent="0"/>
    <mxCell id="2" value="Аналітик" style="shape=umlActor;whiteSpace=wrap;html=1;fillColor=#ffffff;strokeColor=#000000;fontSize=12;verticalLabelPosition=bottom;verticalAlign=top;" vertex="1" parent="1"><mxGeometry x="60" y="20" width="40" height="60" as="geometry"/></mxCell>
    <mxCell id="3" value="Інтерфейс" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" vertex="1" parent="1"><mxGeometry x="200" y="30" width="120" height="40" as="geometry"/></mxCell>
    <mxCell id="4" value="Модуль збору" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontSize=12;" vertex="1" parent="1"><mxGeometry x="380" y="30" width="120" height="40" as="geometry"/></mxCell>
    <mxCell id="5" value="Парсер" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1"><mxGeometry x="560" y="30" width="120" height="40" as="geometry"/></mxCell>
    <mxCell id="6" value="Сховище даних" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1"><mxGeometry x="740" y="30" width="120" height="40" as="geometry"/></mxCell>
    <mxCell id="7" value="Модуль аналізу" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;fontSize=12;" vertex="1" parent="1"><mxGeometry x="920" y="30" width="120" height="40" as="geometry"/></mxCell>
    <mxCell id="l1" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="80" y="80" as="sourcePoint"/><mxPoint x="80" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="l2" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="260" y="70" as="sourcePoint"/><mxPoint x="260" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="l3" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="440" y="70" as="sourcePoint"/><mxPoint x="440" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="l4" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="620" y="70" as="sourcePoint"/><mxPoint x="620" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="l5" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="800" y="70" as="sourcePoint"/><mxPoint x="800" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="l6" style="dashed=1;endArrow=none;html=1;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="980" y="70" as="sourcePoint"/><mxPoint x="980" y="780" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m1" value="1: Налаштувати джерела" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="80" y="130" as="sourcePoint"/><mxPoint x="260" y="130" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m2" value="2: Передати конфігурацію" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="260" y="170" as="sourcePoint"/><mxPoint x="440" y="170" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m3" value="3: Підтвердження" style="html=1;endArrow=open;dashed=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="440" y="210" as="sourcePoint"/><mxPoint x="260" y="210" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m4" value="4: Запустити збір даних" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="80" y="260" as="sourcePoint"/><mxPoint x="260" y="260" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m5" value="5: Ініціювати збір" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="260" y="300" as="sourcePoint"/><mxPoint x="440" y="300" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m6" value="6: Передати сирі дані" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="440" y="340" as="sourcePoint"/><mxPoint x="620" y="340" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m7" value="7: Зберегти оброблені дані" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="620" y="380" as="sourcePoint"/><mxPoint x="800" y="380" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m8" value="8: Підтвердження збереження" style="html=1;endArrow=open;dashed=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="800" y="420" as="sourcePoint"/><mxPoint x="260" y="420" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m9" value="9: Запустити аналіз" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="80" y="480" as="sourcePoint"/><mxPoint x="260" y="480" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m10" value="10: GET /analyze" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="260" y="520" as="sourcePoint"/><mxPoint x="980" y="520" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m11" value="11: Завантажити датасет" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="980" y="560" as="sourcePoint"/><mxPoint x="800" y="560" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m12" value="12: Повернути датасет" style="html=1;endArrow=open;dashed=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="800" y="600" as="sourcePoint"/><mxPoint x="980" y="600" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m13" value="13: Результати + графіки" style="html=1;endArrow=open;dashed=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="980" y="640" as="sourcePoint"/><mxPoint x="260" y="640" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m14" value="14: Відобразити візуалізацію" style="html=1;endArrow=open;dashed=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="260" y="680" as="sourcePoint"/><mxPoint x="80" y="680" as="targetPoint"/></mxGeometry></mxCell>
    <mxCell id="m15" value="15: Експортувати результати" style="html=1;endArrow=block;endFill=1;fontSize=11;" edge="1" parent="1"><mxGeometry relative="1" as="geometry"><mxPoint x="80" y="730" as="sourcePoint"/><mxPoint x="260" y="730" as="targetPoint"/></mxGeometry></mxCell>
  </root>
</mxGraphModel>
```

---

## 3. Activity Діаграма

### Опис
Діаграма діяльності показує покроковий процес роботи системи від авторизації до експорту результатів, включаючи всі розгалуження та петлі повторення.

### XML для draw.io

```xml
<mxGraphModel dx="1422" dy="762" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1169" pageHeight="827" math="0" shadow="0">
  <root>
    <mxCell id="0"/><mxCell id="1" parent="0"/>
    <mxCell id="2" value="" style="ellipse;aspect=fixed;fillColor=#000000;strokeColor=#000000;" vertex="1" parent="1"><mxGeometry x="270" y="20" width="30" height="30" as="geometry"/></mxCell>
    <mxCell id="3" value="Авторизація в системі" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="80" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="4" value="Авторизований?" style="rhombus;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1"><mxGeometry x="205" y="155" width="160" height="60" as="geometry"/></mxCell>
    <mxCell id="4b" value="Повторити вхід" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1"><mxGeometry x="430" y="165" width="160" height="40" as="geometry"/></mxCell>
    <mxCell id="5" value="Налаштувати джерела даних" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="245" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="6" value="Джерела доступні?" style="rhombus;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1"><mxGeometry x="205" y="320" width="160" height="60" as="geometry"/></mxCell>
    <mxCell id="6b" value="Перевірити URL / доступ" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1"><mxGeometry x="430" y="330" width="160" height="40" as="geometry"/></mxCell>
    <mxCell id="7" value="Запустити збір даних" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="410" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="8" value="Фільтрація та очищення даних" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#d5e8d4;strokeColor=#82b366;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="485" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="9" value="Якість даних достатня?" style="rhombus;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1"><mxGeometry x="205" y="560" width="160" height="60" as="geometry"/></mxCell>
    <mxCell id="9b" value="Змінити параметри збору" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#f8cecc;strokeColor=#b85450;fontSize=12;" vertex="1" parent="1"><mxGeometry x="430" y="570" width="160" height="40" as="geometry"/></mxCell>
    <mxCell id="10" value="Аналіз та агрегація даних" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="650" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="11" value="Побудова візуалізацій" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#e1d5e7;strokeColor=#9673a6;fontSize=12;" vertex="1" parent="1"><mxGeometry x="185" y="725" width="200" height="45" as="geometry"/></mxCell>
    <mxCell id="12" value="Потрібен експорт?" style="rhombus;whiteSpace=wrap;html=1;fillColor=#fff2cc;strokeColor=#d6b656;fontSize=12;" vertex="1" parent="1"><mxGeometry x="205" y="800" width="160" height="60" as="geometry"/></mxCell>
    <mxCell id="12b" value="Експорт CSV / PDF / JSON" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#dae8fc;strokeColor=#6c8ebf;fontSize=12;" vertex="1" parent="1"><mxGeometry x="430" y="810" width="160" height="40" as="geometry"/></mxCell>
    <mxCell id="13" value="" style="ellipse;aspect=fixed;fillColor=#000000;strokeColor=#000000;strokeWidth=3;" vertex="1" parent="1"><mxGeometry x="270" y="890" width="30" height="30" as="geometry"/></mxCell>
    <mxCell id="e1" edge="1" source="2" target="3" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e2" edge="1" source="3" target="4" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e3" value="Ні" edge="1" source="4" target="4b" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e4" edge="1" source="4b" target="3" parent="1" style="html=1;endArrow=block;endFill=1;exitX=0.5;exitY=0;entryX=1;entryY=0.5;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e5" value="Так" edge="1" source="4" target="5" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e6" edge="1" source="5" target="6" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e7" value="Ні" edge="1" source="6" target="6b" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e8" edge="1" source="6b" target="5" parent="1" style="html=1;endArrow=block;endFill=1;exitX=0.5;exitY=0;entryX=1;entryY=0.5;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e9" value="Так" edge="1" source="6" target="7" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e10" edge="1" source="7" target="8" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e11" edge="1" source="8" target="9" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e12" value="Ні" edge="1" source="9" target="9b" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e13" edge="1" source="9b" target="7" parent="1" style="html=1;endArrow=block;endFill=1;exitX=0.5;exitY=0;entryX=1;entryY=0.5;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e14" value="Так" edge="1" source="9" target="10" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e15" edge="1" source="10" target="11" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e16" edge="1" source="11" target="12" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e17" value="Так" edge="1" source="12" target="12b" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e18" edge="1" source="12b" target="13" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
    <mxCell id="e19" value="Ні" edge="1" source="12" target="13" parent="1" style="html=1;endArrow=block;endFill=1;"><mxGeometry relative="1" as="geometry"/></mxCell>
  </root>
</mxGraphModel>
```

---

## Як імпортувати в draw.io

1. Відкрий [draw.io](https://app.diagrams.net/)
2. Натисни **Додатково → Редагувати діаграму**
3. Встав XML-код потрібної діаграми
4. Натисни **OK**
