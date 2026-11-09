# Regras de uso da organização | Laboratório de Mastozoologia do MZUSP

Esta organização reúne materiais produzidos no âmbito do Laboratório de Mastozoologia do Museu de Zoologia da Universidade de São Paulo (MZUSP), incluindo protocolos, tutoriais, scripts, pipelines, dados e análises de projetos.

O objetivo é centralizar a produção do laboratório, facilitar o compartilhamento de materiais e preservar o histórico das atividades e contribuições de seus integrantes.

## 1. Criação de repositórios

1. Acesse o template-masto-mzusp e clique em Use this template → Create a new repository.
2. **Owner:** `Masto-MZUSP` (nunca a conta pessoal).
3. Nome: utilize um nome curto, descritivo e em minúsculas, com palavras separadas por hífens. Sempre que possível, siga os padrões abaixo:

| Prefixo | Uso | Exemplo |
|---|---|---|
| `protocolo-` | Protocolos de laboratório, curadoria ou campo | `protocolo-extracao-dna` |
| `pipeline-` | Fluxos de análise reutilizáveis | `pipeline-analise-genomica` |
| `analise-` | Análises de projetos e publicações | `analise-filogeografia-artibeus` |
| `dados-` | Dados e metadados | `dados-ocorrencia-mamiferos` |
| `ensino-` | Cursos e materiais didáticos | `ensino-morfologia-mamiferos` |
| `tutorial-` | Tutoriais de equipamentos e softwares | `tutorial-sequenciador` |

4. **Visibilidade:** utilize inicialmente a opção *Private*. A disponibilização pública deve considerar as restrições de dados, publicações e acordos institucionais.
5. Preencha o `README.md` com informações sobre o conteúdo, autoria, utilização e financiamento. Para materiais citáveis, inclua também o `CITATION.cff`.

## 2. Identificação dos repositórios

Adicione *topics* na seção **About** de cada repositório:

- **Tipo:** `protocolo`, `pipeline`, `analise`, `dados`, `ensino` ou `tutorial`.
- **Responsável:** `nome-sobrenome`.
- **Financiamento:** agência e número do processo, quando aplicável (ex.: `fapesp-2026-12345-0`).
- **Tema:** opcional, conforme o assunto do repositório (ex.: `mastozoologia`, `filogeografia`, `genomica`, `curadoria`).

Utilize apenas letras minúsculas, números e hífens.

## 3. Financiamento e autoria

Na seção **Financiamento** do README, informe os projetos e bolsas que contribuíram diretamente para a produção do material, utilizando o nome completo da agência e o número do processo.

A autoria deve refletir as contribuições efetivas para o desenvolvimento do material. Sempre que pertinente, mantenha essas informações também no `CITATION.cff`.

Para materiais associados a projetos FAPESP, inclua a declaração de responsabilidade exigida pela agência, conforme as orientações vigentes.

## 4. Dados e materiais

- Evite versionar arquivos acima de 50 MB. Arquivos individuais acima de 100 MB não são aceitos pelo GitHub.
- Dados brutos de grande volume devem ser depositados em repositórios apropriados, como SRA, GenBank, Zenodo ou Dryad, com os respectivos links e informações de acesso no README.
- Nunca disponibilize senhas, tokens, dados pessoais ou coordenadas precisas de espécies ameaçadas.
- Respeite as restrições de uso e divulgação de dados, materiais de coleções e informações de terceiros.
- Materiais relacionados ao patrimônio genético devem atender às exigências legais e institucionais aplicáveis, incluindo o cadastro no SisGen quando necessário.

## 5. Versões e citações

Utilize *releases* para identificar versões estáveis de scripts, pipelines, protocolos e outros materiais relevantes (**Releases → Draft a new release**).

Quando integrado ao Zenodo, o *release* poderá gerar um DOI. Atualize o README e o `CITATION.cff` com as informações de citação correspondentes.

## 6. Manutenção e desligamento

Os repositórios permanecem vinculados à organização, mesmo após a saída de seus autores do laboratório.

Antes do desligamento, cada integrante deve, em conjunto com a orientação ou responsável pelo material:

- Atualizar a documentação;
- Registrar o estado atual dos procedimentos e análises;
- Organizar os dados e arquivos associados;
- Criar um *release*, quando pertinente;
- Garantir que a autoria e as contribuições estejam documentadas.

Repositórios vinculados a contas pessoais podem ser transferidos para a organização em **Settings → Transfer ownership**, mediante alinhamento com a orientação.
