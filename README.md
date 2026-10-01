<!-- ======================= HEADER ======================= -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6A5ACD,50:8A2BE2,100:00C9FF&height=220&section=header&text=Matheus%20Freitas&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Desenvolvedor%20Backend%20%C2%B7%20PHP%20%26%20Laravel&descSize=20&descAlignY=60&animation=fadeIn" alt="Header" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=640&height=45&lines=Plataformas+SaaS+multi-tenant;Integra%C3%A7%C3%B5es+REST+%2B+SOAP;Debug+em+produ%C3%A7%C3%A3o+sem+regress%C3%B5es;Backend+escal%C3%A1vel+e+de+alto+desempenho" alt="Typing SVG" />

<br/>

<a href="https://matheusfreitas77.netlify.app/"><img src="https://img.shields.io/badge/PORTF%C3%93LIO-6A5ACD?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfólio" /></a>
<a href="https://www.linkedin.com/in/seu-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:seuemail@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/STATUS-DISPON%C3%8DVEL-2EA043?style=for-the-badge" alt="Disponível" />

</div>

<br/>

<!-- ======================= PORTFÓLIO ======================= -->
<div align="center">

## Meu Portfólio

<a href="https://matheusfreitas77.netlify.app/">
  <img src="https://image.thum.io/get/width/1200/crop/700/https://matheusfreitas77.netlify.app/" alt="Preview do portfólio de Matheus Freitas" width="85%" />
</a>

<br/><br/>

<a href="https://matheusfreitas77.netlify.app/"><img src="https://img.shields.io/badge/ACESSAR_PORTF%C3%93LIO_%E2%86%92-6A5ACD?style=for-the-badge&logoColor=white" alt="Acessar portfólio" /></a>

<sub>Experiência · Cases técnicos · Projetos · Jornada · Laboratório interativo</sub>

</div>

<br/>

<!-- ======================= SOBRE ======================= -->
## Sobre mim

```php
<?php

class Matheus extends Developer
{
    public string $role       = 'Desenvolvedor Backend';
    public string $location   = 'Minas Gerais, BR';
    public int    $experience = 3; // anos+

    public array $focus = [
        'Plataformas SaaS multi-tenant',
        'Integrações críticas via API REST e SOAP (DMS)',
        'Diagnóstico e correção de bugs em produção',
        'Refatoração de código legado com estabilidade',
    ];

    public function philosophy(): string
    {
        return 'Seguir o dado até a origem, em vez de assumir onde ele quebrou.';
    }
}
```

<br/>

<!-- ======================= STACK ======================= -->
## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=php,laravel,js,ts,nodejs,vue,html,css,mysql,postgres,mongodb,docker,git&theme=dark&perline=13" alt="Skills" />

</div>

| Camada | Tecnologias |
| :-- | :-- |
| **Backend** | PHP, Laravel, Node.js, C# (servidor de integração) |
| **Integrações** | API REST, SOAP, Postman |
| **Frontend** | HTML, CSS, JavaScript, TypeScript, Vue.js |
| **Dados** | MySQL, PostgreSQL, MongoDB |
| **Infra** | Docker, Git, redes e suporte N2/N3 |

<br/>

<!-- ======================= EXPERIÊNCIA ======================= -->
## Trajetória

| Período | Papel | Destaque |
| :-- | :-- | :-- |
| **2026 – atual** | Desenvolvedor Full Stack | Sustentação e evolução de SaaS multi-tenant do setor automotivo, com integrações DMS via REST e SOAP |
| **2025 – atual** | Desenvolvedor Web Freelance | Sistemas web sob medida, do levantamento de requisitos à entrega |
| **2024 – atual** | Suporte Técnico N2 → N3 | Infraestrutura de redes, NOC e resolução de incidentes complexos |
| **2025 – 2026** | Instrutor de Informática | Lógica de programação, HTML, CSS e JavaScript, com material didático autoral |
| **2023 – 2024** | Desenvolvedor na 4mti | Sistemas corporativos em PHP e Laravel, APIs REST e MySQL |

<br/>

<!-- ======================= CASES ======================= -->
## Cases técnicos

> Problemas reais de produção que diagnostiquei e corrigi. Detalhes de clientes omitidos por confidencialidade.

<details>
<summary><b>Data de saída em branco no PDF da OS</b></summary>
<br/>

**Sintoma:** a assinatura de saída era gravada, mas data e hora saíam vazias no PDF.

**Causa raiz:** registros duplicados para a mesma OS. O controller buscava sempre o mais recente por chave interna, sem filtrar pelo número da OS, e esse registro era a duplicata incompleta.

**Aprendizado:** o bug "no PDF" nunca esteve no PDF. Seguir o dado até a origem evitou uma refatoração desnecessária.

`Laravel` `SQL` `Eloquent` `Debug em produção`

</details>

<details>
<summary><b>Falha de autenticação SOAP com DMS</b></summary>
<br/>

**Sintoma:** duas lojas do mesmo grupo recebiam erro de senha inválida com o mesmo login que funcionava nas demais.

**Causa raiz:** o DMS valida a credencial junto com o documento da empresa, e o cadastro dessas lojas apontava para outra filial.

**Entrega:** relatório técnico apontando exatamente qual cadastro corrigir, sem alteração de código.

`SOAP` `Postman` `Integração DMS` `Documentação`

</details>

<details>
<summary><b>Cache de fallback para instabilidade do DMS</b></summary>
<br/>

**Problema:** o sistema caía junto com a integração quando o DMS ficava instável.

**Solução:** cache de fallback, para que a tela nunca quebre mesmo com o DMS fora do ar.

</details>

<div align="center">
<a href="https://matheusfreitas77.netlify.app/"><sub>Ver todos os cases no portfólio →</sub></a>
</div>

<br/>

<!-- ======================= PROJETOS ======================= -->
## Galeria de projetos

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Dashboard Financeiro</h4>
      Análise financeira com visualização de dados em tempo real e relatórios personalizados.<br/><br/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h4>Loja Virtual</h4>
      E-commerce completo com carrinho, checkout e integração com pagamentos.<br/><br/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>Sistema de Folha de Ponto</h4>
      Registro e gestão de horas de funcionários, com relatórios de produtividade.<br/><br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
    </td>
    <td width="50%" valign="top">
      <h4>Gestão para Barbearia</h4>
      Agendamento de horários, controle de clientes e gerenciamento de serviços.<br/><br/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
    </td>
  </tr>
</table>

<br/>

<!-- ======================= STATS ======================= -->
## GitHub em números

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=matheusfreitas77&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=6A5ACD&include_all_commits=true" height="165" alt="Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=matheusfreitas77&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA" height="165" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=matheusfreitas77&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=6A5ACD&currStreakLabel=A78BFA" alt="Streak" />

</div>

<br/>

<!-- ======================= CONTATO ======================= -->
<div align="center">

## Vamos conversar?

Disponível para oportunidades e colaborações em projetos desafiadores.

<a href="https://matheusfreitas77.netlify.app/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-6A5ACD?style=for-the-badge&logo=netlify&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/seu-linkedin"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:seuemail@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,50:8A2BE2,100:6A5ACD&height=120&section=footer" alt="Footer" width="100%" />

</div>
