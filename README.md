# notorthesapla
paket  notOrtalamasıHesaplama ;

 java'yı içe aktarın . kullan . Tarayıcı ;

genel  sınıf  Ana {

	public  static  void  main ( String [] args ) {
		
		Tarayıcı  tarayıcı = yeni  Tarayıcı ( Sistem . in );
		
		Sistem . dışarı . print ( "Matematik Notunuz : " );
		int  matematik = tarayıcı . sonrakiInt ();
		Sistem . dışarı . print ( "Fizik Notunuz : " );
		int  fizik = tarayıcı . sonrakiInt ();
		Sistem . dışarı . print ( "Kimya Notunuz : " );
		int  kimya = tarayıcı . sonrakiInt ();
		Sistem . dışarı . print ( "Türkçe Notunuz : " );
		int  türkçe = tarayıcı . sonrakiInt ();
		Sistem . dışarı . print ( "Tarih Notunuz : " );
		int  tarih = tarayıcı . sonrakiInt ();
		Sistem . dışarı . print ( "Müzik Notunuz : " );
		int  muzik = tarayıcı . sonrakiInt ();
		
		int  toplam = ( matematik + fizik + kimya + türkçe + tarih + muzik );
		double  ortalama = toplam / 6 ;
		Sistem . dışarı . println ( "Ortalamanız : " + ortalama );
		
		boolean  gectiMi = ( ortalama > 60 );
		String  kontrol = gectiMi ? "Sınıfı Geçti" : "Sınfta Kaldı" ;
		Sistem . dışarı . println ( kontrol );

	}

}
