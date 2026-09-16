import {View,Image,Text,StyleSheet} from 'react-native';
export default function App() {
  return (
    <View style={styles.content}>
    <View style={styles.conteudo}>
      <View style={styles.logo}>
        <Image 
          source={{uri:'https://butterfliesofbrazil.com.br/wp-content/uploads/2025/01/logo-amarela2.png'}}
          style={styles.image}
        />
      </View>
      <View style={styles.title}>
        <Text style={styles.titleT}>LEPIDOTECA</Text>
      </View>
      <View style={styles.legend}>
        <Text style={styles.legendT}>Catálogo de borboletas brasileiras</Text>
      </View>
    </View>
      <View style={styles.rodape}>
        <Text style={styles.rodapeT}>  v1.0 - Lorena Rodrigues Almeida</Text>
      </View>
    </View>
  );
}
const styles = StyleSheet.create({
  content: {
    flex:1,
    backgroundColor:'#2A3619',
  },
  conteudo:{
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
  },
  logo: {
    backgroundColor:'#A9B596',
    flex:0.35,
    width:'50%',
    marginHorizontal:'25%',
    marginVertical:30,
    alignItems: 'center',
    justifyContent: 'center',
    borderRadius:'20%',
  },
  image: {
    width:125,
    height:120,
  },
  title:{
    alignItems: 'center',
    justifyContent: 'center',
  },
  titleT: {
    fontFamily:'PlayfairDisplay-Bold',
    fontWeight:900,
    fontSize: 40,
    color:'#A9B596',
  },
  legend: {
    backgroundColor:'#2A3619',
    width:'96%',
    marginHorizontal:'2%',
    alignItems:'end',
  },
  legendT:{
    fontFamily:'Montserrat',
    fontWeight: 600,
    fontSize:18,
    fontStyle:'italic',
    color:'#ffdb58',
  },
  rodape: {
    flex:0.05,
    backgroundColor:'#A9B596',
    justifyContent:'center',
  },
  rodapeT:{
    fontSize:12,
    fontStyle:'italic',
  },
});

