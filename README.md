# test-mortgage
 

# створити застосунок для банківської сфери.
<p>Потрібно створити застосунок в якому буде відображатись список створених клієнтом банків.</p>
# При клікові на назву банку - буде відображатись його інформація, а саме:
<ul>
<li>Назва банку</li>
<li>Річна відсоткова ставка по іпотеці (interest rate, %)</li>
<li>Максимальна сума кредиту, яку надає банк (Max loan, $)</li>
<li>Мінімальний платіж (Min payment, $)</li>
<li>Термін кредиту (Loan term)</li>
</ul>
<p>Якщо доданих банків не має - показувати заглушку з текстом: “Банків у списку ще не має”. Для цього потрібно клікнути по кнопці “Create a new bank”.</p>
# Якщо банки в списку є - то відображати інформацію в слідуючому порядку:
<ul>
<li>Порядковий номер</li>
<li>Назва банку</li>
<li>Кнопка по редагуванню</li>
<li>Кнопка по видаленню конкретного банка</li>
<li>Кнопка для створення нового банку. Має бути окремо одна на весь блок</li>
</ul>
# Функції:
<ul>
<li>
<li>Рендер списку банків має здійснювати функція renderList()</li>
<li>Рендер інформації по окремому банку - функція renderInfo()</li>
</ul>
<p>Модалка, де будете вносити дані для нового банку або виводити інфу при правках поточного банку.</p>
# Базові заготовки по розмітці.
Наприклад:
<ul>
<li>контейнер</li>
<li>стилізувати кнопки</li>
<li>добавити іконки</li>
<li>накидати базові стилі (параграфи, списки і т.д.)</li>
<li>створити модалку</li>
</ul>
# Схема банків:
<code>
const banks = [
  {
    id: "435tr34wrt",
    name: "Mono",
    interestRate: 5,
    maxLoan: 500000,
    minPayment: 1000,
    loanTerm: 12,
  },
  {
    id: "asdfw342rew5",
    name: "Privat",
    interestRate: 7,
    maxLoan: 1000000,
    minPayment: 5000,
    loanTerm: 50,
  },</code>
