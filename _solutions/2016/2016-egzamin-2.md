---
layout: page
permalink: /2016/egzamin/2/
---

## 2016 Egzamin poprawkowy

Treść zadań dostępna pod adresem <http://i.imgur.com/wXxtskpg.jpg>.

### Zadanie 1

---

### Zadanie 2

---

### Zadanie 3

Udowodnij, że jeśli turniej nie zawiera skierowanego trójkąta, to można ustawić jego wierzchołki w takiej kolejności \\( v_1, …, v_n \\), że jeśli \\( i < j \\) to \\( v_i \\to v_j \\).

<div data-collapse>
  <h4 class="collapsible">Rozwiązanie</h4>
  <div class="solution">
    <p>
        Lemat: W turnieju bez trójkątów istnieje wierzchołek v, taki że \( deg_{out}(v) = 0 \)
        Dowód:
        Załóżmy, że wierzchołek o najmniejszym stopniu wyjściowym p spełnia \( deg_{out}(p) = k \), gdzie \(k > 0\).
        Każdy wierzchołek \( c \) t. że \( p \to c \) także musi mieć \( deg_{out} \) co najmniej \( k \), ale istnieje
        tylko \( k - 1 \) wierzchołków, do których może prowadzić bez utworzenia trójkąta z \(p\), co prowadzi do sprzeczności z założeniem, że \( p \) ma najmniejszy stopień. Zatem \( k \leq 0 \), czyli \( k = 0 \).

        Teraz możemy usunąć z turnieju wierzchołek o stopniu wychodzącym 0 i zostanie nam \( n-1 \) - turniej, który też nie zawiera skierowanego trójkąta.
        Usuwając z \( k \)-turnieju taki wierzchołek oznaczamy go jako \( v_k \) i w oryginalnym turnieju spełni on warunek danej nam kolejności,
        ponieważ istniała krawędź od niego do wszystkich usuniętych przed nim wierzchołków.
    </p>
  </div>
</div>


---

### Zadanie 4

<div data-collapse>
  <h4 class="collapsible">Rozwiązanie</h4>
  <div class="solution">
    <p>
      <a href="https://math.stackexchange.com/a/398227/237591">
        https://math.stackexchange.com/a/398227/237591
      </a>
    </p>
  </div>
</div>


---
