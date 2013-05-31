#Lekce 1 - Hello World!

První program, který vám v jakémkoliv ukáží se obvykle jmenuje *Hello World*. Tento program dělá jen to, že napíše `Hello World!` na monitor.

Jak může takový program vypadat v jazyce Lua? Třeba takhle:

    -- První program
    print('Hello World!')

Co tam co znamená?

První řádek je komentář. Kdykoliv Lua najde dvě pomlčky za sebou, považuje zbytek řádku za komentář. Komentáře slouží k psaní poznámek pro programátory, k vysvětlení co tento kus kódu znamená, či k dočasnému skrytí nedokončeného nebo nepovedeného kódu před počítačem.

    print('Tohle se napíše') -- print('Tohle už ne, je to komentář')

Druhý řádek je takzvané *volání funkce* `print` s *řetězcem* `'Hello World!'` jako *argumentem*.

Funkce `print` je jedna ze základních funkcí každého programovacího jazyka, slouží k vypisování různých informací. Název `print` má z historických důvodů - první počítače neměly monitory, jen tiskárny.

Volání funkcí se v jazyce Lua (a ve většině ostatních programovacích jazyků) zapisuje stejně: nejprve název funkce, potom otevírací kulatá závorka, pak argumenty (vstup) případně oddělené čárkami a nakonec zavírací kulatá závorka.

Protože funkce `print` příjmá i více parametrů, je možné napsat i:

    print('nazdar', 'pane')

> **Něco navíc**
>
> V některých programovacích jazycích (například v C) je nutné psát za každý příkaz
> středník. Lua to umožňuje, ale nevyžaduje, je tedy možné napsat třeba
>
>     print('A'); print('B')
>

Řetězec (odborný výraz pro text), který má Lua vypsat, jsme uzavřeli do úvozovek, aby počítač opět věděl, kde začíná a končí jazyk počítačový a kde lidský. V jazyce Lua můžete použít jednoduché `'` i dvojité `"`.

> **Pozor!**
>
> Text v úvozovkách nesmí pokračovat na další řádek. Také nesmí obsahovat
> jiné úvozovky stejného druhu v jakém je obalen.
>
> Pokud je chcete do textu dostat,
> musíte před ně napsat zpětné lomítko (`\`) (a pokud chcete do textu zpětné lomítko, musíte napsat dvě za sebou).
>
> Například:
>
>     print('například takto: \\\'')
>
> vypíše jen:
>
>     například takto: \'

Pokud vás poslední odstavec trochu vylekal, tak vězte že právě o hledání překlepů, chybějících čí přebývajících znaků často taky programování je. `:-)`