# SEGAM-(M8.v3.0)-(M8.v7.0)-(M18.v8.0)-(M8.v6.0)-(AN01)

Script de atualização da lista de jogos  
Esse script ajudará a atualizar suas playlists do Game Stick.

📌 **Adiciona suporte para outras versões**

- **Tipo**: `SEGAM-(M8.v3.0)-(M8.v7.0)-(M18.v8.0)-(M8.v6.0)-(AN01)`  

---
### ⚠️ IMPORTANTE
```diff
! CREDITOS PELA CRIAÇÃO DESSE SCRIPT
```
 [KORNCH25](https://4pda.to/forum/index.php?showuser=325008)

---
 [HOSTTOOLS1001](https://github.com/hosttools1001)

---

### 🗂️ Um pouco sobre a estrutura da playlist desse Game Stick

![image](https://github.com/user-attachments/assets/0d7af469-84a6-47ab-86d8-ddde0aaacaba)

Dentro de cada pasta há um arquivo `.dat` que será manipulado pelo script para atualizar a lista de jogos e capas no menu do Game Stick — **não sendo mais necessário acessar ROMs via gerenciador de arquivos**.

---

---

## 🧠 COMO USAR

```diff
! ⚠️ ANTES DE COMEÇAR, FAÇA BACKUP DO SEU CARTÃO SD PARA EVITAR PERDAS!
```

1. Coloque os arquivos `menu.bat` e a pasta `scripts` na **raiz do cartão SD**.  
2. Execute `menu.bat`. O menu de opções será exibido:

![image](https://github.com/user-attachments/assets/3d57cc6e-f336-4745-a3df-22ca8f4ef114)

---

### 🔹 OPÇÃO 1 — Compactar ROMs

- O script verifica e compacta ROMs nas pastas `001` até `006`, caso encontre alguma descompactada.
- **Este passo é opcional!**

```diff
+ Use apenas se achar necessário.
```

![image](https://github.com/user-attachments/assets/bd1f6bc5-bf47-4f00-b5e8-76f01344cc17)

---

### 🖼️ OPÇÃO 2 — Converter capas

- O script converte as **capas dos jogos** adicionados.
- As **capas devem estar no formato `.png .jpg .jpeg`** e **com o mesmo nome da ROM**.

📌 **Exemplo:**

![image](https://github.com/user-attachments/assets/0ceaa688-aebf-471f-966c-d902c7dbcd34)

- Escolha uma pasta de `0` a `14` dependendo da sua versão de sistema para processar.
- Aguarde até o fim — pode demorar dependendo da quantidade de capas.

![image](https://github.com/user-attachments/assets/3b137749-3e34-49ab-a0f2-0fa6c3a2a8ea)

```diff
! OBS: Não é obrigatório adicionar capas nas ROMs.
```

---

### 🧾 OPÇÃO 3 — Criar lista de jogos no menu do emulador
### ⚠️ IMPORTANTE
```diff
! ⚠️ AO CRIAR UMA LISTA PELA PRIMEIRA VEZ TODAS AS CAPAS ORIGINAIS SERAM APAGADAS
! SENDO NECESSARIO ADICIONAR NOVAS CAPAS!
```
- Escolha uma pasta entre `000` e `014`.
- O script criará a lista de jogos e perguntará se deve gerar o arquivo `.dat`.

```diff
+ Confirme para que a ROM seja adicionada ao menu do emulador.
```

![image](https://github.com/user-attachments/assets/39198ba3-28ec-4dbe-a667-20d89485c896)

---

### ✅ Resultado: lista com ROMs adicionadas

![image](https://github.com/user-attachments/assets/f8f9e842-ee9c-48f8-91dd-2f7966ffe033)


### 📋 OPÇÃO 4 — Criar lista da aba geral

- Essa opção cria uma **lista geral de até 200 ROMs por console**, escolhidas aleatoriamente.

![image](https://github.com/user-attachments/assets/e1f5e92a-48d8-46c6-8c70-22688f2ad10a)

```diff
+ As Roms deveram aparecer na lista geral agora
```

### 🖼️ OPÇÃO 5 — Download de capas

- O script analisa as roms da pasta selecionada busca e faz o download da capa referente ao nome da rom
- As **roms nao devem conter caracteres especiais no nome**.

📌 **Exemplo:**

![image](https://github.com/user-attachments/assets/face4971-10b9-41aa-bc20-315daab2bb70)

- Escolha uma pasta de `000` a `014` para processar.
- Aguarde até o fim — pode demorar dependendo da quantidade de capas.

![image](https://github.com/user-attachments/assets/3d319eea-932d-482e-9b80-8db6c2ed8f64)


```diff
! As capas seram baixadas na pasta selecionada use a opção 2 para convertelas.
```

![image](https://github.com/user-attachments/assets/056456ac-724e-4db9-9c6b-f0eae4f055ea)

