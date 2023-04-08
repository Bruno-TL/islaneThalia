<template>
  <v-card>
    <!-- max-width="448" class="mx-auto" -->
    <v-layout>
      <Header class="header" />
      <v-main>
        <v-container  class="container1">
          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 20,00" title="Design simples personalizado"
            variant="text">
            <v-img src="../assets/imgProdutos/dSimples.png" height="128" cover></v-img>

            <v-card-text>
              Ao retirar os pelos excedentes, você pode dar forma e definição às suas sobrancelhas de acordo com o seu
              gosto pessoal.
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                Marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 30,00" title="Design com Henna"
            variant="text">
            <v-img src="../assets/imgProdutos/henna.jpg" height="128" cover></v-img>

            <v-card-text>
              Pigmentação da pele e pelos, capaz de disfarçar falhas e dar mais definiçãoao deginer.
              Técnica ombré: efeito suavizado
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                Marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 35,00" title="Design com Coloração"
            variant="text">
            <v-img src="../assets/imgProdutos/coloracao.png" height="128" cover></v-img>

            <v-card-text>
              Colore pelos e levementre a pele, ideal para quem possui pelos brancos ou claros. Durabilidade até 30 dias ou mais dependendo do tipo de pele.
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 35,00" title="Design Masculino"
            variant="text">
            <v-img src="../assets/imgProdutos/sobrancelha-masculina.jpg" height="128" cover></v-img>

            <v-card-text>
              Retirada de pelos excedentes, respeitando o formado do rosto masculino.
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                Marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 80,00 Alinhamento das sobrancelhas" title="Brow Lamination"
            variant="text">
            <v-img src="../assets/imgProdutos/brow.png" height="128" cover></v-img>
            <v-card-text>
              Inclui design, aplicação do produto Meisheng e nutrição.
            </v-card-text>
            <v-card-text>
              Transforme suas sobrancelhas em uma obra-prima com a técnica revolucionária de brow lamination, que proporciona sobrancelhas perfeitamente modeladas, volumosas e aparentemente mais encorpadas.
            </v-card-text>

            <template v-slot:actions>
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                Marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 50,00" title="SPA das sobrancelhas"
            variant="text">
            <v-img src="../assets/imgProdutos/spa.jpg" height="128" cover></v-img>

            <v-card-text>
              Tratamento com produtos específicos para tratar, cuidar e renovar as células mortas da pele. A técnica proporciona bem-estar e relaxamento, também prepara a pele para garanti maior fixação dos procedimentos.
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          <v-card border class="mb-2 v-cardB" density="compact" subtitle="R$ 10,00 Linha ou Cera" title="Buço"
            variant="text">
            <v-img src="../assets/imgProdutos/buco.png" height="128" cover></v-img>

            <v-card-text>
              Trata-se da remoção dos pelos da região a baixo do nariz, o chamado buço. Oferecendo um resultado duradouro já que são tiradas a partir do nariz.
            </v-card-text>

            <template v-slot:actions>
              <!-- <v-btn color="primary" variant="text">View More</v-btn> -->
              <v-btn class="btn-dark"  color="#ffd700" elevation="24" rounded="lg"  >
                Marcar horário
                <v-icon
                  size="large" 
                  color="green-darken-2" 
                  icon="mdi-whatsapp"
                  end
                  >
                </v-icon>
                </v-btn>
            </template>
          </v-card>

          
        </v-container>
      </v-main>
    </v-layout>
  </v-card>
  <Footer/>
</template>

<script setup>
import Header from "./Header.vue"
import Footer from "./Footer.vue"
  //
</script>

<style>
.btn-dark {
  background-color: rgba(0, 0, 0, 0.937);
}
.v-cardB{
  border: 2px solid #dfbe01 !important;
}

@media (min-width: 768px) {
  .container1{
    display: grid !important;
    grid-template-columns: 50% 50%;
    gap: 15px;
    width: 50%;
    margin: 0 auto;
  }
}
</style>


