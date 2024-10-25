```
Шаблон за извештавање једне рањивости за Metasploitable 3 у Markdown формату.

Формат назива фајла: `VULNX_R2_YY_2024.md`, где је `X` редни број рањивости (тј. 1, 2, 3), а `YY` број индекса.

Уклонити овај део
```

---

**Име и презиме**: Име Презиме

**Тим**: 2

**Датум**: 

**Scan Tool**: Nessus (верзија)

**Тест окружење**: Metasploitable 3 Ubuntu

---

## **1. Енумерација CVE-а**

* **CVE ID**: CVE-...
* **Опис**: ...

---

## **2. CVSS скор**

* **CVSS скор (нумеричка вредност)**: 0.0
* **Вектор**: [доле је наведено за CVSS 2]
  - **Access Vector (AV)**:
  - **Access Complexity (AC)**:
  - **Authentication (AU)**:
  - **Confidentiality (C)**:
  - **Integrity (I)**:
  - **Availability (A)**:
* **Оправдање**:
  - Експлоатабилност ...
  - Impact ...
  - Обим ...

---

## **3. Доступност експлоита**

* **Постоји јавно доступан експлоит (Да/Не)**: ...
* **Опис експлоита**:  ...
* **Код експлоита (уколико постоји)**: слика кода...

---

## **4. Анализа узрока (root cause)**

* **Увођење грешке (commit/верзија)**: ...
* **Пример кода (ако је применљиво)**: слика кода...

---

## **5. Препоруке за митигацију**

* **Да ли је доступан Vendor Fix или patch (Да/Не)**: ...
* **Mitigation strategy**: ...
* **Алтернативни fix (уколико не постоји вендорски)**: ...

---