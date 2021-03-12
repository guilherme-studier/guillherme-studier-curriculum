<template>
    <span>   
        <!-- HEADER -->
        <header-vue>
            <span slot="image">
                <img src="@/assets/images/image.png" />
            </span>
            <span slot="principal">
                <h2>Guilherme Studier</h2>
                <h3>developer junior</h3>
                <div class="info">
                    <div class="row-info">
                        <span class="info-title">Age:</span>
                        <span class="info-desc">23</span>
                    </div>
                    <div class="row-info">
                        <span class="info-title">Phone:</span>
                        <span class="info-desc">+55 (51) 99468-8774</span>
                    </div>
                    <div class="row-info">
                        <span class="info-title">EMAIL:</span>
                        <span class="info-desc">guilherme.studier18@gmail.com</span>
                    </div>
                </div>
                <span class="links">
                    <!-- FACEBOOK -->
                    <a class="link-icon" href="https://www.facebook.com/guilherme.studier" target="_blank" rel="noopener noreferrer"><i class="fab fa-facebook-f"></i></a>
                    <!-- INSTAGRAM -->
                    <a class="link-icon" href="https://www.instagram.com/guilhermestudier/" target="_blank" rel="noopener noreferrer"><i class="fab fa-instagram"></i></a>
                    <!-- LINKEDIN -->
                    <a class="link-icon" href="https://www.linkedin.com/in/guilherme-dos-santos-studier-b65b94195/" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
                    <!-- GITHUB -->
                    <a class="link-icon" href="https://github.com/guilherme-studier" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a>
                </span>
            </span>
        </header-vue>
        <!-- INTRODUÇÃO -->
        <section-content>
            <h2 class="title">Introdução</h2>
                <p>
                    Meu nome é Guilherme dos Santos Studier, em 2020/1 ingressei no tecnólogo de Análise e Desenvolvimento de Sistemas 
                    dentro da Universidade La Salle. Dedico meu tempo a estudar desenvolvimento web com intenção de alcançar o status 
                    de Desenvolvedor Full Stack, dominando o front end e back end. Tenho experiência em trabalhos freelancers que exigiram 
                    conhecimento em HTML, CSS e Javascript e agora busco ampliar meus conhecimentos através de uma experiência profissional 
                    através de um estágio na área da tecnologia.
                </p>
        </section-content>
        <hr>
        <section-content>
            <h3 class="subtitle" style="margin-top: 0px;">Educação</h3>
            <timeline>
                <span slot="university">Universidade La Salle</span>
                <span slot="date">desde 2020</span>
                <span slot="course">Análise e Desenvolvimento de Sistemas</span>
            </timeline>           
        </section-content>
        <hr>
        <section-content>
            <h3 class="subtitle">Skills</h3>
            <grid-items columns="7">
                <skill-item>
                    <img src="@/assets/images/html-css-js.png" />
                    <span>HTML5, CSS3 e JS</span>
                </skill-item>
                <skill-item>
                    <img src="@/assets/images/php.png" />
                    <span>PHP</span>
                </skill-item>
            </grid-items>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Projetos</h3>
            <grid-items columns="3" columns_mobile="1">
                 <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Site | Guilherme Studier</span>
                    <span slot="desc">Projeto de portifólio/currículo para apresentar minhas habilidades, experiências, formação e etc.</span>
                    <span slot="link"><a href="https://guilhermestudier.vercel.app/#/" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span>
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/guillherme-studier-curriculum" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">VueJs, HTML, CSS</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Projeto Churrasco</span>
                    <span slot="desc">Projeto prático final</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/desafio-churrasco" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, PHP</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Tela de Login</span>
                    <span slot="desc">Projeto prático</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/projetoTelaLogin" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, JS</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Projeto Rocketseat</span>
                    <span slot="desc">Projeto prático</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/projeto-rocketseat" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, JS</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Projeto Send Email</span>
                    <span slot="desc">Projeto prático</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/App-Send-Email" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, PHP</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Projeto Help Desk</span>
                    <span slot="desc">Projeto prático</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/app-help-desk" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, PHP</span>
                </card-project>
                <card-project>
                    <span slot="image"><img src="@/assets/images/sistema-de-selecao.png" /></span>
                    <span slot="title">Projeto Spotify</span>
                    <span slot="desc">Projeto prático</span>
                    <!-- <span slot="link"><a href="" target="_blank" rel="noopener noreferrer">Visualizar projeto</a></span> -->
                    <span slot="link-github"><a href="https://github.com/guilherme-studier/projeto-spotify" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i></a></span>
                    <span slot="list">HTML, CSS, PHP</span>
                </card-project>
            </grid-items>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Cursos de extensão</h3>
            <timeline>
                <span slot="university">Udemy</span>
                <span slot="date">03/2021</span>
                <span slot="course">Curso Desenvolvimento Web Completo</span>
            </timeline>
            <timeline>
                <span slot="university">School of Net</span>
                <span slot="date">10/2020</span>
                <span slot="course">HTML básico a intermediário</span>
            </timeline>
            <timeline>
                <span slot="university">School of Net</span>
                <span slot="date">10/2020</span>
                <span slot="course">CSS básico a intermediário</span>
            </timeline>
            <timeline>
                <span slot="university">School of Net</span>
                <span slot="date">10/2020</span>
                <span slot="course">JS básico a intermediário</span>
            </timeline>
        </section-content>
        <hr />
        <section-content>
            <h3 class="subtitle">Idiomas</h3>
            <grid-items columns="7" columns_mobile="1">
                <skill-item>
                    <img src="@/assets/images/ingles.png" />
                    <span>Inglês - Intermediário</span>
                </skill-item>
            </grid-items>
            <br />
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
