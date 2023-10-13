/*********************************************************VALIDAÇÃO FRASE 1***********************************************************/
import hashlib

myText = 'A primeira das instituições criadas pelo Pe. Roberto Sabóia de Medeiros foi a antiga Escola Superior de Administração de Negócios de São Paulo - ESAN/SP.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 2***********************************************************/
import hashlib

myText = 'A FEI é uma instituição vinculada estatutariamente à Companhia de Jesus'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 3***********************************************************/
import hashlib

myText = 'Em 20 de janeiro de 1951 foi realizada a sessão solene da congregação para a Colação de Grau da primeira turma da Faculdade de Engenharia Industrial.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 4***********************************************************/
import hashlib

myText = 'A Capela Santo Inácio de Loyola foi construída no ano de 1978, em concreto aparente.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 5***********************************************************/
import hashlib

myText = 'Tendo como função principal a promoção do aprimoramento profissional no campo administrativo e tecnológico, o IECAT (Instituto de Especialização em Ciências Administrativas e Tecnológicas) foi criado em 1982'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 6***********************************************************/
import hashlib

myText = 'Dentro de uma proposta de integração e de agregação de competências, visando a excelência de seus cursos, as instituições FEI, FCI e ESAN foram transformadas no Centro Universitário da FEI no ano de 2002.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 7***********************************************************/
import hashlib

myText = 'O Centro Universitário da FEI passou a fazer parte do seleto grupo que produz ciência no Brasil, quando a CAPES aprovou o primeiro curso de Mestrado em Engenharia Elétrica em 2005.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 8***********************************************************/
import hashlib

myText = 'Em 2016 foi realizada a primeira edição do congresso de inovação - Megatendências 2050.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 9***********************************************************/
import hashlib

myText = 'Em 2012 o Centro Universitário FEI celebrou 70 anos de história e de excelência na inovação e na formação de mais de 50 mil profissionais altamente qualificados para o setor empresarial, entre Administradores, Engenheiros e Cientistas da Computação.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)

/*********************************************************VALIDAÇÃO FRASE 10***********************************************************/
import hashlib

myText = 'Em 1999 iniciam-se as atividades da FCI (Faculdade de Informática), como o curso de Ciência da Computação.'

SHA256 = hashlib.sha256(myText.encode('utf-8')).hexdigest()
MD5 = hashlib.md5(myText.encode('utf-8')).hexdigest()

print("\"" +myText + "\" - " + SHA256 + " - " + MD5)
