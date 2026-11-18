# Guia de Contribuição

## Fluxo de trabalho
1. Crie uma branch a partir da `main`:
   ```
   git checkout -b tipo/descricao-curta
   ```
2. Faça commits pequenos e frequentes.
3. Envie a branch: `git push -u origin nome-da-branch`
4. Abra um Pull Request usando o modelo.
5. Revise o próprio código antes de fazer o merge.

## Nomes de branch
Use o mesmo tipo do commit, seguido de `/` e uma descrição curta.
Exemplo: `feat/cadastro-usuario`

## Convenção de commits
Formato: `tipo: descrição curta`

| Tipo | Quando usar |
|---|---|
| feat | nova funcionalidade |
| fix | correção de bug |
| docs | documentação |
| test | testes |
| refactor | reorganização sem mudar comportamento |
| chore | manutenção e configuração |

Exemplos:
- `feat: adiciona cálculo de streak`
- `fix: corrige validação de e-mail`

Regras:
- Primeira linha com até ~72 caracteres e sem ponto final
- Verbo no presente (adiciona, corrige, remove)
- Um commit = uma mudança lógica

## Antes de abrir o Pull Request
- [ ] Testes passando
- [ ] Nenhum segredo (senha, chave, token) no código
- [ ] Documentação atualizada quando necessário
