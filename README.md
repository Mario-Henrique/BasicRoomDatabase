# BasicRoomDatabase
App em kotlin mostrando um uso de banco de dados

Primeiro precisamos definir as dependências:
  * No arquivo build.gradle(module app):
    * adicionar o plugin kapt: "id 'kotlin-kapt'"
    * em dependencies adicionar as dependências para uso do room:
      * implementation "androidx.room:room-runtime:2.2.6"
      * implementation "androidx.room:room-ktx:2.2.6"
      * kapt "androidx.room:room-compiler:2.2.6"
    * Vamos também usar o lifecycle:
      * implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.3.0"
      * implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.3.0"
      * implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.3.0"
    * O número após os 2 pontos se refere a versão do mesmo. Troque pela mais recente.
