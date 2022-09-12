# Dubtes

## HTML

1. Header hauria de ser la caixa gran o la subcaixa que conté logo nav i social?

2. Està bé posar sempre id als elements únics i class als elements repetibles?

## CSS

3. Normalment com se solucionen els marges entre elements en què els dels extrems no han de tenir marges?

   Container:

   ```css
   margin: 0 calc((margin / 2) * -1);
   ```

   Elements:

   ```css
   margin: 0 calc(margin / 2);
   ```

4. És bona solució la de la graella d'articles?

   Container:

   ```css
   display: flex;
   gap: gap;
   ```

   Elements:

   ```css
   width: calc(50% - (gap / 2);
   ```
