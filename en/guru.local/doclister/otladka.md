
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<h2>DocLister: Отладка</h2>

<p>Для отладки работы сниппета используется параметр <code>&debug</code>.</p>
<p><span class="text-bold">Возможные значения:</span> -2, -1, 0, 1, 2. 1 покажет только SQL-запросы; 2 - весь стек работы снипета (какие чанки использовались, какие данные подставлялись и т.д.) Минус влияет лишь на положение блока с отладочной информацией (больше нуля - до результатов работы сниппета, а меньше нуля - после).</p>
<p><span class="text-bold">Значение по умолчанию</span> - 0.</p>