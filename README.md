import { StyleSheet, Text, View,TouchableOpacity, } from 'react-native'
import React from 'react'

const Privacysetting = () => {
  return (
    <View style={styles.container}>
          <View style={styles.wrapper}>
          <Text style={styles.text}>𝘗𝘳𝘪𝘷𝘢𝘤𝘺 𝘚𝘦𝘵𝘵𝘪𝘯𝘨𝘴</Text>
          </View>
          <View>
          <TouchableOpacity style={styles.button}><Text style={{fontSize:30, padding:10, textAlign:'center', fontWeight:'bold', color: '#0808ec',}}>English</Text></TouchableOpacity>
          </View>
          <View>
          <TouchableOpacity style={styles.button1}><Text style={{fontSize:30, padding:10, textAlign:'center', fontWeight:'bold', color: '#0808ec',}}>தமிழ்</Text></TouchableOpacity>
          </View>
          <View>
          <TouchableOpacity style={styles.button2}><Text style={{fontSize:30, padding:10, textAlign:'center', fontWeight:'bold',  color: '#0808ec',}}>සිංහල</Text></TouchableOpacity>
          </View>
      </View>
  )
}

export default Privacysetting

const styles = StyleSheet.create({
    container: {
        flex: 1,
        backgroundColor: "#ad2179"
    },
    text: {
        color: '#000000',
        fontSize: 25,
        textAlign:'center',
    },
    button: {
        backgroundColor: "#FFFFFF",
        borderRadius: 50,
        width: 'auto',
        alignSelf: 'center',
        marginTop: 450,
        marginBottom: 30,

    },
    button1: {
        backgroundColor: "#FFFFFF",
        borderRadius: 50,
        width: 'auto',
        alignSelf: 'center',
        marginBottom: 30,
    },
    button2: {
        backgroundColor: "#FFFFFF",
        borderRadius: 50,
        width: 'auto',
        alignSelf: 'center',
        marginBottom: 30,
    },
    wrapper: {
        backgroundColor:"#FFFFFF",
    },
}
)
