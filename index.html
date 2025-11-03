<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comunicação com Motoristas - Controle por Agente</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 14px;
        }

        textarea {
            height: 100px;
            resize: vertical;
        }

        .radio-group, .checkbox-group {
            display: flex;
            gap: 20px;
            margin-top: 10px;
            flex-wrap: wrap;
        }

        .radio-option, .checkbox-option {
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .agent-selector {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-top: 10px;
        }

        .agent-btn {
            padding: 12px;
            border: 2px solid #ddd;
            border-radius: 5px;
            background: white;
            cursor: pointer;
            text-align: center;
            transition: all 0.3s;
        }

        .agent-btn:hover {
            border-color: #007bff;
            background: #f0f8ff;
        }

        .agent-btn.selected {
            border-color: #007bff;
            background: #007bff;
            color: white;
        }

        .btn {
            background-color: #007bff;
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            width: 100%;
            margin-top: 10px;
        }

        .btn:hover {
            background-color: #0056b3;
        }

        .btn-secondary {
            background-color: #28a745;
            margin-top: 10px;
        }

        .btn-secondary:hover {
            background-color: #218838;
        }

        .stats-section {
            margin-top: 40px;
        }

        .agent-stats, .leadership-sheet {
            margin-top: 20px;
            padding: 20px;
            background-color: #f8f9fa;
            border-radius: 5px;
            border-left: 4px solid #007bff;
        }

        .leadership-sheet {
            border-left-color: #28a745;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }

        .stat-item {
            background: white;
            padding: 15px;
            border-radius: 5px;
            border: 1px solid #ddd;
            text-align: center;
        }

        .leader {
            background: #fff3cd;
            border-color: #ffc107;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            background: white;
        }

        th, td {
            padding: 12px;
            text-align: left;
            border: 1px solid #ddd;
        }

        th {
            background-color: #f8f9fa;
            font-weight: bold;
        }

        .timestamp {
            font-size: 12px;
            color: #666;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>📞 Comunicação com Motoristas - Controle por Agente</h1>
        
        <form id="communicationForm">
            <div class="form-group">
                <label for="agentSelect">Agente Responsável:</label>
                <div class="agent-selector">
                    <div class="agent-btn" data-agent="Aline">Aline</div>
                    <div class="agent-btn" data-agent="Joel">Joel</div>
                    <div class="agent-btn" data-agent="Davi">Davi</div>
                </div>
                <input type="hidden" id="selectedAgent" name="selectedAgent" required>
            </div>

            <div class="form-group">
                <label for="driverMessage">Mensagem para o Driver:</label>
                <textarea id="driverMessage" name="driverMessage" placeholder="Digite a mensagem que será enviada para o motorista..." required></textarea>
            </div>

            <div class="form-group">
                <label for="messageSent">Mensagem Enviada:</label>
                <textarea id="messageSent" name="messageSent" placeholder="Descreva a mensagem que foi efetivamente enviada..." required></textarea>
            </div>

            <div class="form-group">
                <label for="driverResponse">Retorno do Driver:</label>
                <textarea id="driverResponse" name="driverResponse" placeholder="Registre o retorno recebido do motorista..."></textarea>
            </div>

            <div class="form-group">
                <label>Destinatário da Mensagem:</label>
                <div class="radio-group">
                    <div class="radio-option">
                        <input type="radio" id="toDriver" name="recipient" value="driver" required>
                        <label for="toDriver">Apenas Driver</label>
                    </div>
                    <div class="radio-option">
                        <input type="radio" id="toSupport" name="recipient" value="support">
                        <label for="toSupport">Apenas Suporte</label>
                    </div>
                    <div class="radio-option">
                        <input type="radio" id="toBoth" name="recipient" value="both">
                        <label for="toBoth">Ambos</label>
                    </div>
                </div>
            </div>

            <div class="form-group">
                <label for="orderId">ID do Pedido:</label>
                <input type="text" id="orderId" name="orderId" placeholder="Digite o ID do pedido..." required>
            </div>

            <div class="form-group">
                <label for="logOl">Log da OL:</label>
                <textarea id="logOl" name="logOl" placeholder="Registre o log da OL..." required></textarea>
            </div>

            <div class="form-group">
                <label>Status do Envio:</label>
                <div class="checkbox-group">
                    <div class="checkbox-option">
                        <input type="checkbox" id="sentToDriver" name="sentToDriver">
                        <label for="sentToDriver">Enviado para Driver</label>
                    </div>
                    <div class="checkbox-option">
                        <input type="checkbox" id="sentToSupport" name="sentToSupport">
                        <label for="sentToSupport">Enviado para Suporte</label>
                    </div>
                </div>
            </div>

            <button type="submit" class="btn">💾 Registrar Comunicação</button>
        </form>

        <!-- Seção de Estatísticas por Agente -->
        <div class="stats-section">
            <div class="agent-stats">
                <h3>📊 Estatísticas Mensais por Agente</h3>
                <div class="stats-grid" id="agentStats">
                    <!-- As estatísticas serão preenchidas dinamicamente -->
                </div>
            </div>

            <!-- Planilha para Liderança -->
            <div class="leadership-sheet">
                <h3>📋 Planilha para Liderança - Resumo Mensal</h3>
                <button onclick="generateLeadershipSheet()" class="btn btn-secondary">🔄 Atualizar Planilha</button>
                
                <div id="leadershipTable">
                    <table>
                        <thead>
                            <tr>
                                <th>Agente</th>
                                <th>Total de Casos</th>
                                <th>Para Driver</th>
                                <th>Para Suporte</th>
                                <th>Para Ambos</th>
                                <th>Último Registro</th>
                            </tr>
                        </thead>
                        <tbody id="leadershipTableBody">
                            <!-- Dados preenchidos via JavaScript -->
                        </tbody>
                    </table>
                </div>

                <div id="monthlySummary" style="margin-top: 20px;">
                    <!-- Resumo mensal será gerado aqui -->
                </div>
            </div>
        </div>
    </div>

    <script>
        // Dados armazenados localmente (em produção, use um banco de dados)
        let communications = JSON.parse(localStorage.getItem('communications')) || [];
        let selectedAgent = '';

        // Seleção de agente
        document.querySelectorAll('.agent-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                document.querySelectorAll('.agent-btn').forEach(b => b.classList.remove('selected'));
                this.classList.add('selected');
                selectedAgent = this.getAttribute('data-agent');
                document.getElementById('selectedAgent').value = selectedAgent;
            });
        });

        // Submit do formulário
        document.getElementById('communicationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            if (!selectedAgent) {
                alert('Por favor, selecione um agente responsável.');
                return;
            }

            const formData = {
                id: Date.now(),
                agent: selectedAgent,
                timestamp: new Date().toLocaleString('pt-BR'),
                date: new Date().toISOString().split('T')[0],
                driverMessage: document.getElementById('driverMessage').value,
                messageSent: document.getElementById('messageSent').value,
                driverResponse: document.getElementById('driverResponse').value,
                recipient: document.querySelector('input[name="recipient"]:checked').value,
                orderId: document.getElementById('orderId').value,
                logOl: document.getElementById('logOl').value,
                sentToDriver: document.getElementById('sentToDriver').checked,
                sentToSupport: document.getElementById('sentToSupport').checked
            };

            // Salvar no localStorage
            communications.push(formData);
            localStorage.setItem('communications', JSON.stringify(communications));

            // Atualizar estatísticas
            updateAgentStats();
            updateLeadershipSheet();

            alert(`Comunicação registrada com sucesso para ${selectedAgent}!`);
            this.reset();
            document.querySelectorAll('.agent-btn').forEach(b => b.classList.remove('selected'));
            selectedAgent = '';
        });

        function updateAgentStats() {
            const statsContainer = document.getElementById('agentStats');
            const currentMonth = new Date().toISOString().slice(0, 7); // YYYY-MM
            
            // Filtrar comunicações do mês atual
            const monthlyComms = communications.filter(comm => 
                comm.date.startsWith(currentMonth)
            );

            // Calcular estatísticas por agente
            const agentStats = {
                'Aline': monthlyComms.filter(comm => comm.agent === 'Aline').length,
                'Joel': monthlyComms.filter(comm => comm.agent === 'Joel').length,
                'Davi': monthlyComms.filter(comm => comm.agent === 'Davi').length
            };

            const total = monthlyComms.length;
            const leader = Object.entries(agentStats).reduce((a, b) => a[1] > b[1] ? a : b);

            statsContainer.innerHTML = '';

            Object.entries(agentStats).forEach(([agent, count]) => {
                const percentage = total > 0 ? ((count / total) * 100).toFixed(1) : 0;
                const isLeader = agent === leader[0] && count > 0;
                
                const statItem = document.createElement('div');
                statItem.className = `stat-item ${isLeader ? 'leader' : ''}`;
                statItem.innerHTML = `
                    <strong>${agent}</strong><br>
                    <span style="font-size: 24px; color: ${isLeader ? '#ff6b00' : '#007bff'};">${count}</span> casos<br>
                    <small>${percentage}% do total</small>
                    ${isLeader ? '<br><small>🏆 Líder do mês</small>' : ''}
                `;
                statsContainer.appendChild(statItem);
            });

            // Item de total geral
            const totalItem = document.createElement('div');
            totalItem.className = 'stat-item';
            totalItem.innerHTML = `
                <strong>Total Geral</strong><br>
                <span style="font-size: 24px; color: #28a745;">${total}</span> casos<br>
                <small>Mês ${currentMonth.split('-').reverse().join('/')}</small>
            `;
            statsContainer.appendChild(totalItem);
        }

        function updateLeadershipSheet() {
            const tableBody = document.getElementById('leadershipTableBody');
            const currentMonth = new Date().toISOString().slice(0, 7);
            
            const monthlyComms = communications.filter(comm => 
                comm.date.startsWith(currentMonth)
            );

            const agentData = {
                'Aline': { total: 0, driver: 0, support: 0, both: 0, lastDate: '' },
                'Joel': { total: 0, driver: 0, support: 0, both: 0, lastDate: '' },
                'Davi': { total: 0, driver: 0, support: 0, both: 0, lastDate: '' }
            };

            // Calcular dados para cada agente
            monthlyComms.forEach(comm => {
                const agent = comm.agent;
                agentData[agent].total++;
                
                if (comm.recipient === 'driver') agentData[agent].driver++;
                if (comm.recipient === 'support') agentData[agent].support++;
                if (comm.recipient === 'both') agentData[agent].both++;
                
                // Manter a data mais recente
                if (!agentData[agent].lastDate || comm.date > agentData[agent].lastDate) {
                    agentData[agent].lastDate = comm.date;
                }
            });

            tableBody.innerHTML = '';

            Object.entries(agentData).forEach(([agent, data]) => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td><strong>${agent}</strong></td>
                    <td>${data.total}</td>
                    <td>${data.driver}</td>
                    <td>${data.support}</td>
                    <td>${data.both}</td>
                    <td>${data.lastDate ? new Date(data.lastDate).toLocaleDateString('pt-BR') : 'N/A'}</td>
                `;
                tableBody.appendChild(row);
            });

            // Atualizar resumo mensal
            updateMonthlySummary();
        }

        function updateMonthlySummary() {
            const summaryContainer = document.getElementById('monthlySummary');
            const currentMonth = new Date().toLocaleDateString('pt-BR', { month: 'long', year: 'numeric' });
            const totalCases = communications.filter(comm => 
                comm.date.startsWith(new Date().toISOString().slice(0, 7))
            ).length;

            const leader = getCurrentLeader();

            summaryContainer.innerHTML = `
                <div style="background: white; padding: 15px; border-radius: 5px; margin-top: 15px;">
                    <h4>📈 Resumo do Mês de ${currentMonth}</h4>
                    <p><strong>Total de casos registrados:</strong> ${totalCases}</p>
                    <p><strong>Líder em atendimentos:</strong> ${leader.name} com ${leader.count} casos</p>
                    <p><strong>Média por agente:</strong> ${Math.round(totalCases / 3)} casos</p>
                    <p class="timestamp">Última atualização: ${new Date().toLocaleString('pt-BR')}</p>
                </div>
            `;
        }

        function getCurrentLeader() {
            const currentMonth = new Date().toISOString().slice(0, 7);
            const monthlyComms = communications.filter(comm => 
                comm.date.startsWith(currentMonth)
            );

            const counts = {
                'Aline': monthlyComms.filter(comm => comm.agent === 'Aline').length,
                'Joel': monthlyComms.filter(comm => comm.agent === 'Joel').length,
                'Davi': monthlyComms.filter(comm => comm.agent === 'Davi').length
            };

            const leader = Object.entries(counts).reduce((a, b) => a[1] > b[1] ? a : b, ['', 0]);
            return { name: leader[0], count: leader[1] };
        }

        function generateLeadershipSheet() {
            updateLeadershipSheet();
            alert('Planilha de liderança atualizada com sucesso!');
            
            // Aqui você pode adicionar a funcionalidade para exportar para Excel/PDF
            console.log('=== PLANILHA PARA LIDERANÇA ===');
            console.log('Dados prontos para exportação:');
            console.log(JSON.stringify(communications, null, 2));
        }

        // Inicializar estatísticas ao carregar a página
        document.addEventListener('DOMContentLoaded', function() {
            updateAgentStats();
            updateLeadershipSheet();
        });
    </script>
</body>
</html>
