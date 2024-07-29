## `<table>` - Tabele
    ```bash
    <table> <!-- Table - Tworzy tabele-->
        <tr> <!-- Table Row - wiersz poziomy tabeli-->
            <td>wiersz 1 kolumna 1</td> <!-- Table Data - Definiuje komórke w tabeli-->
            <td>wiersz 1 kolumna 2</td>
            <td>wiersz 1 kolumna 3</td>
        </tr>
        <tr>
            <td>wiersz 2 kolumna 1</td>
            <td>wiersz 2 kolumna 2</td>
            <td>wiersz 2 kolumna 3</td>
        </tr>
    </table>


    <br>

    <table>
        <caption>Podpis tabeli:</caption> <!-- Tytuł/Nazwa Tabeli ->
      <thead> <!-- Nagłówek Tabeli - Definiujemy w nim poszczególne nazwy kolumn ->
          <tr>
              <td></td>
              <td>Kolumna 1</td>
              <td>Kolumna 2</td>
          </tr>
      </thead>
      <tbody> <!-- Table Body - Właściwa Treść Tabeli ->
          <tr>
              <td>Wiersz 1</td>
              <td>200</td>
              <td>300</td>
          </tr>
          <tr>
              <td>Wiersz 2</td>
              <td>200</td>
              <td>300</td>
          </tr>
          <tr>
              <td>Wiersz 3</td>
              <td>400</td>
              <td>500</td>
          </tr>
      </tbody>
      <tfoot> <!-- Table Footer - Stopka Tabeli ->
          <tr>
              <td>Podsumowanie:</td>
              <td>800</td>
              <td>1100</td>
          </tr>
      </tfoot>
    </table>
    ```
    ### Result
    <table>
      <tr>
          <td>wiersz 1 kolumna 1</td>
          <td>wiersz 1 kolumna 2</td>
          <td>wiersz 1 kolumna 3</td>
      </tr>
      <tr>
          <td>wiersz 2 kolumna 1</td>
          <td>wiersz 2 kolumna 2</td>
          <td>wiersz 2 kolumna 3</td>
      </tr>
    </table>
    
    
    <br>
    
    <table>
      <caption>Podpis tabeli:</caption>
      <thead>
          <tr>
              <td></td>
              <td>Kolumna 1</td>
              <td>Kolumna 2</td>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>Wiersz 1</td>
              <td>200</td>
              <td>300</td>
          </tr>
          <tr>
              <td>Wiersz 2</td>
              <td>200</td>
              <td>300</td>
          </tr>
          <tr>
              <td>Wiersz 3</td>
              <td>400</td>
              <td>500</td>
          </tr>
      </tbody>
      <tfoot>
          <tr>
              <td>Podsumowanie:</td>
              <td>800</td>
              <td>1100</td>
          </tr>
      </tfoot>
    </table>
    
    ## `<a>` - hiperłącze
    
<!--
http://127.0.0.1/ - localhost - adres na naszym komputerze
-->

```bash
  <p><a href="https://google.com">link bezwzględny - absolutny</a></p>

  <p><a href="lists.html">link względny - relative</a></p>
  <p><a href="./lists.html">link względny z ./ - relative</a></p> <!-- Odnosi sie tylko do katalogu  k troym znajdue sie plik-->


  <p><a href="/lists.html">link względny z / - relative</a></p>  <!-- Zawsze odnosi sie do głownego katalogu -->

  <p>
      <a href="tel:48987987987">987987987</a> <!-- Dzwoni po kliknięciu -->
  </p>

  <p>
      <a href="mailto:ewa@example.com">ewa@example.com</a> <!-- Przechodzi do domyślnego maila -->
  </p>

  <p>
      <a href="#">pusty link</a> <!-- Pusty hash potrzebny do JavaScirpt -->
  </p>


  <!-- kotwice - z angielskiego anchors -->
  <p>
      <a href="#chapter1">rozdział #1</a> <!-- Przechodzi do treści na stornie -->
  </p>

  <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptate quisquam voluptatibus iure neque cum id
      modi pariatur. Consectetur pariatur, perferendis, laboriosam ducimus nulla ab asperiores suscipit recusandae
      esse culpa ea nobis cum ratione voluptates, debitis vitae? Nesciunt, magnam voluptate nostrum quisquam
      doloremque deserunt sint est earum, minima id ipsam? Hic, porro quasi dolore nemo ipsam ut iste nulla
      dolorem earum tenetur iure natus expedita eaque quae provident quos sit. Placeat reprehenderit, voluptates
      accusantium, aliquam aut praesentium voluptatibus aspernatur amet maiores dolorum quis magni cumque rerum
      dolores? Sunt, asperiores ipsam eligendi provident aspernatur quidem accusamus molestiae quia modi earum
      veniam officiis.
  </p>

  <h3 id="chapter1">Nagłówek h3 - rozdział #1</h3>
  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iste provident laborum unde minima assumenda optio
      quisquam porro, necessitatibus debitis fuga odio hic perspiciatis autem soluta vitae alias? Sequi optio
      reiciendis aut dolorum illo voluptatum aspernatur sed dolores facilis ratione minima saepe inventore,
      dignissimos tempora aliquid numquam. Nam minus eum molestiae. Id ab in vero, odio perferendis vel veritatis
      illum sapiente facilis amet. Veritatis, id nisi quo, quasi fuga expedita adipisci ducimus, iusto
      necessitatibus delectus consequuntur. Sint id ratione accusamus unde minima, quae commodi hic dignissimos
      maiores? Voluptas velit distinctio laudantium culpa unde, quibusdam, modi vel aut laboriosam facilis error!
      Minima.</p>
```

  <p><a href="https://google.com">link bezwzględny - absolutny</a></p>

  <p><a href="lists.html">link względny - relative</a></p>
  <p><a href="./lists.html">link względny z ./ - relative</a></p>


  <p><a href="/lists.html">link względny z / - relative</a></p>

  <p>
      <a href="tel:48987987987">987987987</a>
  </p>

  <p>
      <a href="mailto:ewa@example.com">ewa@example.com</a>
  </p>

  <p>
      <a href="#">pusty link</a>
  </p>


  <!-- kotwice - z angielskiego anchors -->
  <p>
      <a href="#chapter1">rozdział #1</a>
  </p>

  <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptate quisquam voluptatibus iure neque cum id
      modi pariatur. Consectetur pariatur, perferendis, laboriosam ducimus nulla ab asperiores suscipit recusandae
      esse culpa ea nobis cum ratione voluptates, debitis vitae? Nesciunt, magnam voluptate nostrum quisquam
      doloremque deserunt sint est earum, minima id ipsam? Hic, porro quasi dolore nemo ipsam ut iste nulla
      dolorem earum tenetur iure natus expedita eaque quae provident quos sit. Placeat reprehenderit, voluptates
      accusantium, aliquam aut praesentium voluptatibus aspernatur amet maiores dolorum quis magni cumque rerum
      dolores? Sunt, asperiores ipsam eligendi provident aspernatur quidem accusamus molestiae quia modi earum
      veniam officiis.
  </p>

  <h3 id="chapter1">Nagłówek h3 - rozdział #1</h3>
  <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Iste provident laborum unde minima assumenda optio
      quisquam porro, necessitatibus debitis fuga odio hic perspiciatis autem soluta vitae alias? Sequi optio
      reiciendis aut dolorum illo voluptatum aspernatur sed dolores facilis ratione minima saepe inventore,
      dignissimos tempora aliquid numquam. Nam minus eum molestiae. Id ab in vero, odio perferendis vel veritatis
      illum sapiente facilis amet. Veritatis, id nisi quo, quasi fuga expedita adipisci ducimus, iusto
      necessitatibus delectus consequuntur. Sint id ratione accusamus unde minima, quae commodi hic dignissimos
      maiores? Voluptas velit distinctio laudantium culpa unde, quibusdam, modi vel aut laboriosam facilis error!
      Minima.</p>
