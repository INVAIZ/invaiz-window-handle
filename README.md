# `invaiz-window-handle`

πΌππ·π₯β `Windows`, `macOS`μμ λͺ¨λ μ¬μ©ν  μ μλ ν¬λ‘μ€ νλ«νΌ `Window Handler`, μ°½ μ‘°μ, κ΄λ¦¬ κΈ°λ₯μ `npm`μ ν΅ν΄ λ°°ν¬νλ νλ‘μ νΈμλλ€.

- `npm install invaiz-window-handle` λͺλ Ήμ΄λ₯Ό ν΅ν΄ λ€μ΄ λ°μ μ¬μ©ν  μ μμ΅λλ€.

```shell
npm install invaiz-window-handle
```

- μ¬μ©

```ts
import WindowHandle from "invaiz-window-handle";

WindowHandle.senMeesage("messageType", "actionType", "typeKey", 0);
```

- λ§€κ°λ³μ
  - `meesageType`: μ‘μ ν  λ©μΈμ§μ νμ.
  - `actionType`: μ‘μ ν  νλμ νμ.
  - `typeKey`: μ‘μ ν  ν€μ νμ.
  - `s`: μ‘μ ν  λ©μΈμ§μ ν¨κ» λκΈΈ κ°.
  
- λ°ν κ°: κ²°κ³Ό κ°μ `string` νμμΌλ‘ λ°ν.
  - λΉμ μμ μΈ νλμΌ κ²½μ° `Error!` λ°ν.
  - `try { ... } catch (e) { ... }`λ₯Ό μ¬μ©νμ§ μμ μ μλλ‘ μλ¬ μΊμΉ.
