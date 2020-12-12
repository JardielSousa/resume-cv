<template>
  <section class="resume-section experience-section mb-5">
    <h2 class="resume-section-title text-uppercase font-weight-bold pb-3 mb-3">Experiência de Trabalho</h2>
    <div class="resume-section-content">
      <div class="resume-timeline position-relative">
        
        <ResumeTimelineItem class="pb-5"
          position-title="Desenvolvedor Backend II"
          company-name="Ília Digital"
          position-time="2020 - Presente"
          :technologies-used="['Java','Oracle Database','Api Rest','Docker','Docker Compose','Git','Spring Boot','Feign']">
          Criação/Manutenção de microservices. Implementação de novas funcionalidades, 
          execução de atividades mensais usando o SCRUM como ferramenta de gerenciamento 
          de atividades.
        </ResumeTimelineItem>
        
        <ResumeTimelineItem class="pb-5"
          position-title="Desenvolvedor Sênior"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2018 - 2020"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery','Api Rest']">
          Manutenção de ERP para planos de saúde. Correções de falhas, 
          implementação de novas funcionalidades, participação de planejamento 
          e execução de atividades mensais usando o SCRUM como ferramenta de gerenciamento 
          de atividades. Participação de definições de planejamento estratégico. Implementação 
          de novas features para a mudança de arquitetura da aplicação. Criação de biblioteca REST 
          para comunição entre aplicações.
        </ResumeTimelineItem>
        
        <ResumeTimelineItem class="pb-5"
          position-title="Desenvolvedor Pleno"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2015 - 2018"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery','Api Rest']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas 
          funcionalidades, participação de planejamento e execução de atividades mensais usando o 
          SCRUM como ferramenta de gerenciamento de atividades. Participação de definições de 
          planejamento estratégico. Implementação de novas features para a mudança de arquitetura 
          da aplicação. Criação de biblioteca REST para comunição entre aplicações.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem class="pb-5"
          position-title="Desenvolvedor Júnior"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2014 - 2015"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas 
          funcionalidades, participação de planejamento e execução de atividades mensais usando o 
          SCRUM como ferramenta de gerenciamento de atividades.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem class="pb-5"
          position-title="Estagiário em programação"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2013 - 2014"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas 
          funcionalidades e execução de tarefas usando SCRUM.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem class="pb-5"
          position-title="Técnico em Informática"
          company-name="Freelancer"
          position-time="2008 - 2012"
          :technologies-used="[]">
          Suporte técnico em computadores, notebooks, impressoras etc.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem
          position-title="Técnico de suporte"
          company-name="Netsoft Tecnologia"
          position-time="2007 - 2008"
          :technologies-used="['DBF', 'Clipper']">
          Suporte de sistema para controle de vendas e estoque de fármacias e comércios em geral.
        </ResumeTimelineItem>
        
      </div><!--//resume-timeline-->
    </div>
  </section><!--//experience-section-->
</template>

<script>
import ResumeTimelineItem from "./ResumeTimelineItem.vue";

export default {
  name: "experienceSection",
  components: { ResumeTimelineItem }
}
</script>

<style>

</style>