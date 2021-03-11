<template>
    <span>   
        <!-- HEADER -->
        <header-vue>
            <span slot="image">
                <img src="@/assets/images/perfil.jpg" />
            </span>
            <span slot="principal">
                <h2>Guilherme Studier</h2>
                <h3>fullstack developer junior</h3>
                <div class="info">
                    <div class="row-info">
                        <span class="info-title">Age:</span>
                        <span class="info-desc">23</span>
                    </div>
                    <div class="row-info">
                        <span class="info-title">Phone:</span>
                        <span class="info-desc">+55 (51) 99236-5609</span>
                    </div>
                    <div class="row-info">
                        <span class="info-title">EMAIL:</span>
                        <span class="info-desc">guilherme.studier18@gmail.com</span>
                    </div>
                </div>
                <span class="links">
                    <!-- FACEBOOK -->
                    <a class="link-icon" href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-facebook-f"></i></a>
                    <!-- INSTAGRAM -->
                    <a class="link-icon" href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-instagram"></i></a>
                    <!-- LINKEDIN -->
                    <a class="link-icon" href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
                    <!-- GITHUB -->
                    <a class="link-icon" href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a>
                    <!-- BITBUCKET -->
                    <a class="link-icon" href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-bitbucket"></i></a>
                </span>
            </span>
        </header-vue>
        <!-- INTRODUÇÃO -->
        <section-content>
            <h2 class="title">Introdução</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate quidem ab explicabo pariatur molestias facilis, et impedit suscipit doloremque dolor obcaecati soluta, necessitatibus quo architecto vitae animi accusantium voluptates fugit.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate quidem ab explicabo pariatur molestias facilis, et impedit suscipit doloremque dolor obcaecati soluta, necessitatibus quo architecto vitae animi accusantium voluptates fugit.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate quidem ab explicabo pariatur molestias facilis, et impedit suscipit doloremque dolor obcaecati soluta, necessitatibus quo architecto vitae animi accusantium voluptates fugit.</p>
        </section-content>
        <hr>
        <section-content>
            <h3 class="subtitle" style="margin-top: 0px;">Educação</h3>
            <timeline>
                <span slot="university">Instituição</span>
                <span slot="date">desde 2000</span>
                <span slot="course">Curso</span>
            </timeline>           
        </section-content>
        <hr>
        <section-content>            
            <h3 class="subtitle">Experiência</h3>
            <timeline>
                <span slot="university">Empresa</span>
                <span slot="date">desde 2000</span>
                <span slot="course">Cargo</span>
            </timeline>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Skills</h3>
            <grid-items columns="7">
                <skill-item>
                    <img src="@/assets/images/html-css-js.png" />
                    <span>HTML5, CSS3 e JS</span>
                </skill-item>
            </grid-items>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Projetos</h3>
            <grid-items columns="3" columns_mobile="1">
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Nome do projeto</span>
                    <span slot="desc">Descrição do projeto</span>
                    <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span>
                    <span slot="link-github"><a href="" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">Tecnologias</span>
                </card-project>
            </grid-items>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Cursos de extensão</h3>
            <timeline>
                <span slot="university">Instituição</span>
                <span slot="date">00/0000</span>
                <span slot="course">Curso</span>
            </timeline>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Idiomas</h3>
            <grid-items columns="7" columns_mobile="1">
                <skill-item>
                    <img src="@/assets/images/portugues.png" />
                    <span>Idioma - Nível</span>
                </skill-item>
            </grid-items>
            <br />
            <timeline>
                <span slot="university">Instituição</span>
                <span slot="date">desde 00/0000</span>
                <span slot="course">Curso</span>
            </timeline>
        </section-content>
        <footer-vue>
            © 2021 • Todos os direitos reservador • Thiago Studier
        </footer-vue>
    </span>
</template>

<script>

import HeaderVue from '@/components/includes/HeaderVue';
import SectionContent from '@/components/includes/SectionContent';
import Timeline from '@/components/includes/Timeline.vue';
import SkillItem from '@/components/includes/SkillItem.vue';
import GridItems from '@/components/includes/GridItems.vue';
import CardProject from '@/components/includes/CardProject.vue';
import FooterVue from '@/components/includes/FooterVue.vue';

export default {
    name: 'Home',
    components:{
        HeaderVue,
        SectionContent,
        Timeline,
        SkillItem,
        GridItems,
        CardProject,
        FooterVue
    },
    data () {
        return {
      
        }
    }
}
</script>

<style scoped>
</style>
