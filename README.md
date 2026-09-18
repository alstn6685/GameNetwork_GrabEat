# GameNetwork_GrabEat

# 2조 팀원
- 김재성
- 김민수
- 홍재모

# 대표패킷 5가지
Client to Server

type1 로그인
{
	받을 정보 유저ID, 비밀번호
}

type2 로그아웃
{
	
}

type5 플레이어 이동
{
	좌표값
}

Server to Client

type11 방코드
{
	방코드
}

type12 접속여부
{
	접속여부
}

type13 결과창
{
	승패여부
}

type14 아이템 정보
{
	아이템ID,
	아이템 위치값
}

type15 다른 플레이어 정보
{
	좌표값
}