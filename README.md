<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Acolhimento - CAPS AD Antônio Orlando</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  font-family: Arial, sans-serif;
  background: #f4f6f8;
  margin: 0;
}

header {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 20px;
}

.container {
  max-width: 1000px;
  margin: 20px auto;
  background: white;
  padding: 25px;
  border-radius: 10px;
}

h2 {
  border-bottom: 2px solid #eee;
  padding-bottom: 5px;
  margin-top: 25px;
}

label {
  display: block;
  margin-top: 10px;
  font-weight: bold;
}

input, select, textarea {
  width: 100%;
  padding: 8px;
  margin-top: 4px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

.inline {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.inline label {
  font-weight: normal;
}

.row {
  display: flex;
  gap: 10px;
}

.row div {
  flex: 1;
}

button {
  margin-top: 20px;
  padding: 12px;
  width: 100%;
  background: #3498db;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 16px;
}

.print-btn {
  background: #27ae60;
}
</style>

<script>
function imprimir() {
  window.print();
}
</script>

</head>

<body>

<header>
<h1>CAPS AD Antônio Orlando</h1>
<p>Ficha de Acolhimento</p>
</header>

<div class="container">

<form>

<h2>1. Identificação</h2>

<label>Nome completo</label>
<input type="text">

<div class="row">
<div>
<label>Data de nascimento</label>
<input type="date">
</div>

<div>
<label>Idade</label>
<input type="number">
</div>
</div>

<label>Nome da mãe</label>
<input type="text">

<label>CPF</label>
<input type="text">

<label>Telefone</label>
<input type="text">

<label>Endereço completo</label>
<input type="text">

<div class="row">
<div>
<label>Bairro</label>
<input type="text">
</div>

<div>
<label>Cidade</label>
<input type="text">
</div>
</div>

<h2>2. Dados Sociais</h2>

<label>Estado civil</label>
<select>
<option>Solteiro</option>
<option>Casado</option>
<option>União estável</option>
<option>Divorciado</option>
</select>

<label>Escolaridade</label>
<select>
<option>Fundamental incompleto</option>
<option>Fundamental completo</option>
<option>Médio incompleto</option>
<option>Médio completo</option>
<option>Superior</option>
</select>

<label>Situação de trabalho</label>
<input type="text">

<label>Renda</label>
<input type="text">

<h2>3. Uso de Substâncias</h2>

<label>Substâncias utilizadas</label>
<textarea></textarea>

<label>Idade de início</label>
<input type="text">

<label>Frequência de uso</label>
<input type="text">

<label>Último uso</label>
<input type="date">

<label>Já apresentou abstinência?</label>
<select>
<option>Sim</option>
<option>Não</option>
</select>

<h2>4. Saúde Mental</h2>

<label>Diagnóstico prévio</label>
<input type="text">

<label>Uso de medicação psiquiátrica</label>
<textarea></textarea>

<label>Histórico de internação</label>
<textarea></textarea>

<label>Ideação suicida</label>
<select>
<option>Não</option>
<option>Passado</option>
<option>Atual</option>
</select>

<h2>5. Saúde Clínica</h2>

<label>Doenças clínicas</label>
<textarea></textarea>

<label>Uso de medicação contínua</label>
<textarea></textarea>

<h2>6. Rede de Apoio</h2>

<label>Possui apoio familiar?</label>
<select>
<option>Sim</option>
<option>Não</option>
</select>

<label>Com quem reside?</label>
<input type="text">

<label>Referência familiar</label>
<input type="text">

<h2>7. Situação Atual</h2>

<label>Motivo da procura</label>
<textarea></textarea>

<label>Encaminhamento</label>
<input type="text">

<label>Situação de risco</label>
<textarea></textarea>

<!-- EXAME DO ESTADO MENTAL -->

<h2>8. Exame do Estado Mental</h2>

<label>Aparência</label>
<div class="inline">
<label><input type="checkbox"> Preservada</label>
<label><input type="checkbox"> Prejudicada</label>
<label><input type="checkbox"> Odor fétido</label>
<label><input type="checkbox"> Lesões aparentes</label>
<label><input type="checkbox"> Vestes não condizentes</label>
</div>

<label>Consciência</label>
<div class="inline">
<label><input type="checkbox"> Consciente</label>
<label><input type="checkbox"> Obnubilado</label>
<label><input type="checkbox"> Torporoso</label>
</div>

<label>Orientação Autopsíquica</label>
<div class="inline">
<label><input type="checkbox"> Sim</label>
<label><input type="checkbox"> Não</label>
</div>
<input type="text" placeholder="Se não, qual alteração">

<label>Orientação Alopsíquica</label>
<div class="inline">
<label><input type="checkbox"> Sim</label>
<label><input type="checkbox"> Não</label>
</div>

<label>Atenção</label>
<div class="inline">
<label><input type="checkbox"> Normovigil</label>
<label><input type="checkbox"> Hipervigil</label>
<label><input type="checkbox"> Hipovigil</label>
</div>

<label>Memória</label>
<div class="inline">
<label><input type="checkbox"> Preservada</label>
<label><input type="checkbox"> Alterada</label>
</div>
<input type="text" placeholder="Tipo de alteração na memória">

<label>Linguagem</label>
<div class="inline">
<label><input type="checkbox"> Normal</label>
<label><input type="checkbox"> Prolixo</label>
<label><input type="checkbox"> Lacônico</label>
<label><input type="checkbox"> Logorreico</label>
<label><input type="checkbox"> Mutismo</label>
</div>

<label>Afetividade</label>
<div class="inline">
<label><input type="checkbox"> Associado</label>
<label><input type="checkbox"> Dissociado</label>
<label><input type="checkbox"> Embotado</label>
</div>

<label>Humor</label>
<div class="inline">
<label><input type="checkbox"> Eutímico</label>
<label><input type="checkbox"> Eufórico</label>
<label><input type="checkbox"> Disfórico</label>
<label><input type="checkbox"> Irritável</label>
<label><input type="checkbox"> Ansioso</label>
<label><input type="checkbox"> Deprimido</label>
</div>

<label>Psicomotricidade</label>
<div class="inline">
<label><input type="checkbox"> Agitação psicomotora</label>
<label><input type="checkbox"> Inalterada</label>
<label><input type="checkbox"> Lentificação psicomotora</label>
</div>

<label>Pensamento</label>
<div class="inline">
<label><input type="checkbox"> Organizado</label>
<label><input type="checkbox"> Desorganizado</label>
<label><input type="checkbox"> Lentificado</label>
<label><input type="checkbox"> Acelerado</label>
<label><input type="checkbox"> Delirante</label>
<label><input type="checkbox"> Ideação suicida</label>
<label><input type="checkbox"> Persecutoriedade</label>
</div>

<label>Tipo de delírio ou persecutoriedade</label>
<input type="text">

<label>Alucinações</label>
<div class="inline">
<label><input type="checkbox"> Sim</label>
<label><input type="checkbox"> Não</label>
</div>

<label>Tipo de alucinação</label>
<input type="text">

<label>Síntese do exame mental</label>
<textarea></textarea>

<h2>9. Projeto Terapêutico Inicial</h2>

<label>Conduta inicial</label>
<textarea></textarea>

<label>Encaminhamentos</label>
<textarea></textarea>

<label>Profissional responsável</label>
<input type="text">

<label>Data</label>
<input type="date">

<button type="submit">Salvar (visual)</button>
<button type="button" class="print-btn" onclick="imprimir()">Imprimir / PDF</button>

</form>

</div>

</body>
</html>
