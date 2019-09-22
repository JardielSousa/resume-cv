<template>
  <section class="resume-section experience-section mb-5">
    <h2 class="resume-section-title text-uppercase font-weight-bold pb-3 mb-3">Experiência de Trabalho</h2>
    <div class="resume-section-content">
      <div class="resume-timeline position-relative">
        
        <ResumeTimelineItem
          position-title="Desenvolvedor Sênior"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2018 - Presente"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery','Api Rest']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas funcionalidades, participação de planejamento e execução de atividades mensais usando o SCRUM como ferramenta de gerenciamento de atividades. Participação de definições de planejamento estratégico. Implementação de novas features para a mudança de arquitetura da aplicação. Criação de biblioteca REST para comunição entre aplicações.
        </ResumeTimelineItem>
        
        <ResumeTimelineItem
          position-title="Desenvolvedor Pleno"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2015 - 2018"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery','Api Rest']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas funcionalidades, participação de planejamento e execução de atividades mensais usando o SCRUM como ferramenta de gerenciamento de atividades. Participação de definições de planejamento estratégico. Implementação de novas features para a mudança de arquitetura da aplicação. Criação de biblioteca REST para comunição entre aplicações.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem
          position-title="Desenvolvedor Júnior"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2014 - 2015"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas funcionalidades, participação de planejamento e execução de atividades mensais usando o SCRUM como ferramenta de gerenciamento de atividades.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem
          position-title="Estagiário em programação"
          company-name="Infoway Tecnologia e Gestão em Saúde"
          position-time="2013 - 2014"
          :technologies-used="['Java','Postgresql','sql','Servlet','HTML/CSS','Jquery']">
          Manutenção de ERP para planos de saúde. Correções de falhas, implementação de novas funcionalidades e execução de tarefas usando SCRUM.  
        </ResumeTimelineItem>
        
        <ResumeTimelineItem
          position-title="Técnico em Informática"
          company-name="Freelancer"
          position-time="2008 - 2012"
          :technologies-used="[]">
          Suporte técnico em computadores, notebooks, impressoras etc.  
        </ResumeTimelineItem>
        
        <article class="resume-timeline-item position-relative">
          
          <div class="resume-timeline-item-header mb-2">
            <div class="d-flex flex-column flex-md-row">
                <h3 class="resume-position-title font-weight-bold mb-1">Técnico de suporte</h3>
                <div class="resume-company-name ml-auto">Netsoft Tecnologia</div>
            </div><!--//row-->
            <div class="resume-position-time">2007 - 2008</div>
          </div><!--//resume-timeline-item-header-->
          <div class="resume-timeline-item-desc">
            <p>Suporte de sistema para controle de vendas e estoque de fármacias e comércios em geral.</p>
            <h4 class="resume-timeline-item-desc-heading font-weight-bold">Technologies used:</h4>
            <ul class="list-inline">
              <li class="list-inline-item"><span class="badge badge-primary badge-pill">DBF</span></li>
              <li class="list-inline-item"><span class="badge badge-primary badge-pill">Clipper</span></li>
            </ul>
          </div><!--//resume-timeline-item-desc-->

        </article><!--//resume-timeline-item-->
        
        
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