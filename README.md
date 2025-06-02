# DataControl

**Gerencie dados do seu navegador com total controle, segurança e praticidade.**

O **DataControl** é uma aplicação inteligente para visualizar, importar, exportar e organizar dados armazenados no LocalStorage de forma intuitiva. Ideal para desenvolvedores, analistas de dados e qualquer pessoa que deseje entender ou manipular dados persistentes do navegador sem complicações.

---

## ✨ Funcionalidades Principais

- ✔️ **Visualização Intuitiva:** painel moderno e responsivo para explorar os dados organizados por categorias.
- ✔️ **Exportação Simples:** exporta dados completos ou segmentados em formatos otimizados.
- ✔️ **Importação Segura:** importa dados externos com validação automática.
- ✔️ **Armazenamento Local:** todos os dados são salvos localmente, dispensando servidores externos.
- ✔️ **Segurança Avançada:** controle de acesso e criptografia opcional.
- ✔️ **Atualizações em Tempo Real:** todas as modificações são refletidas instantaneamente.

---

## 🔄 Como Funciona

1. **Acesse o Sistema:** login direto pelo navegador, sem instalações.
2. **Visualize seus Dados:** filtre, organize e analise com facilidade.
3. **Importe e Exporte:** com poucos cliques, seus dados estão prontos para uso.
4. **Obtenha Insights:** dashboards com métricas e KPIs em tempo real.

---

## 🎓 Tecnologias Utilizadas

- **React.js** com TailwindCSS para interface responsiva
- **LocalStorage API** para persistência local
- **JavaScript Modular** com ES6+

---

## 📊 Exemplo de Uso

```js
import { clients } from './data';
import Chart from './components/Chart';

export default function Dashboard() {
  return (
    <div className="p-6">
      <Chart
        data={clients}
        title="Growth Metrics"
        colors={['#3b82f6', '#0d9488']}
      />
    </div>
  );
}
```

---

## 🌐 Acesse Agora

**[https://betinribeiro.github.io/datacontrol](https://betinribeiro.github.io/datacontrol)**

---

## ✍️ Autor

**Rogoberto Ribeiro**  
[GitHub](https://github.com/betinribeiro) | [LinkedIn](https://www.linkedin.com/in/rogoberto)

---

## ✉️ Contato

Para dúvidas, feedbacks ou colaborações:
- Email: usbetin@gmail.com
- WhatsApp: (88) 98112-6816

---

## ✅ Licença

Este projeto está licenciado sob a MIT License.
