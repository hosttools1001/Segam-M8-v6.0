# Segam-M8-v6.0

Script de atualização da lista de jogos  
Esse script ajudará a atualizar suas playlists do Game Stick.

📌 **Testado somente no Game Stick Little 4K**

- **Tipo**: `segam-m8-v6.0`  
- **Firmware**: `V1.0.0 2023-09-25`

---
### ⚠️ IMPORTANTE

```diff
! CREDITOS PELA CRIAÇÃO DESSE SCRIPT
! KORNCH25
! https://4pda.to/forum/index.php?showuser=325008
! HOSTTOOLS1001
! https://github.com/hosttools1001
```

---

### 🗂️ Um pouco sobre a estrutura da playlist desse Game Stick

![image](https://github.com/user-attachments/assets/c08114af-53dc-474a-855a-a34392aa9614)

Dentro de cada pasta há um arquivo `.dat` que será manipulado pelo script para atualizar a lista de jogos e capas no menu do Game Stick — **não sendo mais necessário adicionar ROMs via gerenciador de arquivos**.

---

### ⚠️ IMPORTANTE

```diff
! O SCRIPT CRIA ARQUIVOS TEMPORÁRIOS NO DIRETÓRIO MANIPULADO.
! VERIFIQUE SE HÁ ESPAÇO DISPONÍVEL NO CARTÃO SD PARA EVITAR ERROS!
```

---

## 🧠 COMO USAR

```diff
! ⚠️ ANTES DE COMEÇAR, FAÇA BACKUP DO SEU CARTÃO SD PARA EVITAR PERDAS!
```

1. Coloque os arquivos `menu.bat` e a pasta `scripts` na **raiz do cartão SD**.  
2. Execute `menu.bat`. O menu de opções será exibido:

![image](https://github.com/user-attachments/assets/2f9c3d72-e8b8-43e4-a92a-7835faecb13c)

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

- Escolha uma pasta de `0` a `8` para processar.
- Aguarde até o fim — pode demorar dependendo da quantidade de capas.

![image](https://github.com/user-attachments/assets/caa04971-d196-4380-83ce-6bf51ec038a0)

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
- Escolha uma pasta entre `000` e `008`.
- O script criará a lista de jogos e perguntará se deve gerar o arquivo `.dat`.

```diff
+ Confirme para que a ROM seja adicionada ao menu do emulador.
```

![image](https://github.com/user-attachments/assets/f3b8466d-841e-493e-a269-ded44d1528da)

---

### ✅ Resultado: lista com ROMs adicionadas

![image](https://github.com/user-attachments/assets/f8f9e842-ee9c-48f8-91dd-2f7966ffe033)


### 📋 OPÇÃO 4 — Criar lista da aba geral

- Essa opção cria uma **lista geral de até 200 ROMs por console**, escolhidas aleatoriamente.

![image](https://github.com/user-attachments/assets/e1f5e92a-48d8-46c6-8c70-22688f2ad10a)

```diff
+ As Roms deveram aparecer na lista geral agora
```
