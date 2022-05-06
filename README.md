# La radio guerrilla


String url = "http://giss.tv:8000/guerrillaradio.ogg"; // your URL here
    MediaPlayer mediaPlayer = new MediaPlayer();
    mediaPlayer.setAudioStreamType(AudioManager.STREAM_MUSIC);
    mediaPlayer.setDataSource(url);
    mediaPlayer.prepare(); // might take long! (for buffering, etc)
    mediaPlayer.start();
    
