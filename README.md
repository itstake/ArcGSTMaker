Arcaea GST Maker v1.0.0 by EATSTEAK

이 프로그램은 Arcaea 의 GST(Game SoundTrack) 을 만들어 주는 배치파일입니다.
64-bit Windows 10에서 동작을 확인하였습니다.

== 사용법 ==
1.agstmaker.bat 파일을 실행합니다.
2.프로그램의 지시대로 따릅니다.

추가로 설정하고 싶은 부분이 있는데 어떻게 하는지 모르겠다면 아래를 보세요.


== instant.bat 은 무엇인가요? ==
해당 파일은 GST Maker 를 설정 과정 없이 곧바로 실행할 수 있습니다.
대신 obb 파일은 instant.bat 이 있는 폴더에 main.obb 라는 이름으로 저장되어 있어야 하며,
dl 폴더는 같은 폴더에 dl 이라는 이름의 폴더로,
앨범아트 폴더는 같은 폴더의 albumarts 라는 이름의 폴더로,
songlist 와 packlist 파일은 같은 폴더에 존재해야 합니다.
또한 설정은 전부 기본값으로 되어 있습니다.
이를 수정하시려면 instant.bat 파일을 직접 수정하셔야 합니다.

== DL 폴더 안내 ==
DL 폴더는 안드로이드 휴대폰 기준으로 루팅을 하여야만 복사해올 수 있습니다.
루팅을 한 경우 파일 관리자 등으로 /data/data/moe.low.arc/files/dl 폴더를 그대로 복사해서 프로그램이 요구할 때 끌어넣으시면 됩니다.

== 커스텀 앨범 아트 안내 ==
만약 앨범아트 방법을 바꾸어서 자신이 만든(혹은 다른 사람이 배포한) 앨범 아트를 적용하고 싶다면
앨범 아트를 넣을 폴더를 만든 다음에(프로그램에서 끌어 넣으라고 하는 폴더를 만드는 것입니다.)
자신이 원하는 앨범 아트 방식에 따라 아래 단계를 따르세요.

=== 모든 곡의 앨범 아트를 하나로 통일하고 싶은 경우 ===

1.만든 앨범아트 폴더에 원하는 앨범 아트(.jpg 혹은 .png) 를 넣으세요.
2.앨범아트 이름은 arcaea_all 으로 바꾸세요.
3.앨범아트 폴더를 프로그램에서 요구할때 자신이 넣은 앨범아트가 있는 폴더를 끌어넣으세요.
4.앨범아트 표시 방식은 전체로 선택하세요.

=== 각 팩마다 앨범아트를 지정하고 싶은 경우 ===

1.만든 앨범아트 폴더에 원하는 앨범 아트(.jpg 혹은 .png) 를 넣으세요.
2.앨범아트 이름은 해당 팩의 코드네임(Maker 내부의 packlist 파일을 메모장 등으로 열면 id 부분에 있습니다)으로 바꾸세요.
예) 기본 arcaea 팩의 경우 base 로 이름을 바꾸면 됩니다.
3.앨범아트 폴더를 프로그램에서 요구할때 자신이 넣은 앨범아트가 있는 폴더를 끌어넣으세요.
4.앨범아트 표시 방식은 팩으로 선택하세요.

=== Arcaea 에서 삭제된 곡(만우절 곡)을 추가하고 싶은 경우 ===
1.앨범아트 폴더 안에 삭제된 곡의 코드명(삭제된 곡의 songlist id)으로 된 폴더를 만드세요.
2.해당 곡의 앨범아트를 폴더 안에 넣고, base.jpg 라는 이름으로 변경하세요.(이 경우는 jpg밖에 지원하지 않습니다.)