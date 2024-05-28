# Day 1 | Network Devices | Packet Tracer Introduction | Lab

이 글은 Jeremy’s IT Lab의 유튜브 CCNA 200-301 과정을 참고하고 정리한 내용입니다.

[https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ](https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ)

# Network Devices
<img width="1487" alt="Untitled" src="https://github.com/leew0nseok/network-study/assets/101381258/87ee16fa-4c54-46df-9818-cb5892940141">

- 클라이언트: 서버에서 제공하는 서비스에 액세스하는 장치
- 서버: 클라이언트는 서버일 수도 있음. 서버는 클라이언트에게 기능이나 서비스를 제공

<img width="904" alt="Untitled 1" src="https://github.com/leew0nseok/network-study/assets/101381258/a3880614-9fee-432d-9ffc-bb378653db77">


PC1: 클라이언트 

PC2: 서버 
<img width="1444" alt="Untitled 2" src="https://github.com/leew0nseok/network-study/assets/101381258/e07a8823-eb03-45a0-86c1-592d54145f5d">


컴퓨터의 데이터가 인터넷을 통해 유튜브 서버에 도달함. 
<img width="1224" alt="Untitled 3" src="https://github.com/leew0nseok/network-study/assets/101381258/00d4fd29-1b77-410e-bdca-e1f57cc0fd82">


동일한 장치가 어떤 상황에서는 클라이언트가 어떤 상황에서는 서버가 될 수 있음. 
<img width="1690" alt="Untitled 4" src="https://github.com/leew0nseok/network-study/assets/101381258/c75808f6-c52b-41d3-abd8-b8fc0487638e">

<img width="1450" alt="Untitled 5" src="https://github.com/leew0nseok/network-study/assets/101381258/2903427b-64e5-435c-8097-0ef52dce8193">


- 스위치
    - PC와 같은 최종 호스트가 연결할 수 있는 많은 네트워크 인터페이스 또는 포트(보통 24개 이상)가 있음
    - 동일한 LAN, 즉 근거리 통신망 내의 호스트에 대한 연결을 제공함
    - 스위치는 LAN간 또는 인터넷을 통한 연결을 제공하지 않음. 그러기 위해서는 또 다른 종류의 네트워크 장치가 필요 → 라우터

<img width="1692" alt="Untitled 6" src="https://github.com/leew0nseok/network-study/assets/101381258/32358f23-f5db-4e2f-a3b3-fa6fed6acd34">



스위치를 라우터에 연결한 다음 라우터를 인터넷에 연결할 수 있음.
<img width="1598" alt="Untitled 7" src="https://github.com/leew0nseok/network-study/assets/101381258/34c9b713-d3e0-4206-b9b7-e0ea4ae2f0da">


- ISR 1000과 IST 4000은 뒷면에 네트워크 인터페이스가 있지만 ISR 900을 보면 라우터와 스위치의 차이점을 볼 수 있음.
- 예를들어 )스위치 Catalyst 9200 시리즈 스위치에 비해 ISR 900 라우터는 네트워크 인터페이스가 상대적으로 적음
<img width="1686" alt="Untitled 8" src="https://github.com/leew0nseok/network-study/assets/101381258/13b7d7fa-f9e0-4739-b826-74c7ac5ff1bc">


- 몇 가지 기본적인 보안 기능을 제공할 수 있지만 네트워크를 보호하기 위해 실제로 사용해야 하는 것은 바로 방화벽임.
- 방화벽은 네트워크에 들어오고 나가는 네트워크 트래픽을 제어하는 특수 네트워크 보안 장치임.
- 방화벽은 FW1과 같이 라우터 외부에 배치하거나 FW2와 같이 라우터 내부에 배치
- 어떤 네트워크 트래픽을 허용하고 거부할지 결정
<img width="1393" alt="Untitled 9" src="https://github.com/leew0nseok/network-study/assets/101381258/e736043e-97f4-4d8c-8f3e-ccd4692fe6c7">


- 방화벽 특징
    - 방화벽은 구성된 규칙에 따라 네트워크 트래픽을 모니터링하고 제어함.
    - 네트워크 내부에 배치하거나 외부에 배치할 수 있음. 어떤 경우에는 내부와 외부에 있을 수 있음.

## Quiz 1
<img width="1651" alt="Untitled 10" src="https://github.com/leew0nseok/network-study/assets/101381258/ba005b14-fad1-4a55-b8d5-d62bbe4e79ac">


정답: c

A인 라우터의 경우는 PC와 같은 많은 호스트를 연결하는 것이 아니라 네트워크 간에 트래픽을 전달하도록 설계되었음. B인 방화벽의 경우는 네트워크 트래픽을 필터링. D 서버의 경우 다른 최종 호스트를 연결하는 네트워킹 장치가 아니라 최종 호스트 자체임. 

## Quiz 2
<img width="1683" alt="Untitled 11" src="https://github.com/leew0nseok/network-study/assets/101381258/501fb072-c6bd-42d0-9daa-1584a4ac3ea7">


정답: a

내 iphone의 경우 클라이언트이며 친구의 경우 서버임. 

## Quiz 3
<img width="1648" alt="Untitled 12" src="https://github.com/leew0nseok/network-study/assets/101381258/1ad72b06-14f9-4984-9676-d3d7a9b20d8a">

정답: c

이 동영상을 볼때 클라이언트 역할을 한다. 내 장치는 최종 소트긴하지만 기능을 설명하지는 않기때문에 b는 아니다. 

## Quiz 4
<img width="1657" alt="Untitled 13" src="https://github.com/leew0nseok/network-study/assets/101381258/a26c4ddf-390a-4188-8bbb-99b2a0679182">


정답: d

## Quiz 5
<img width="1694" alt="Untitled 14" src="https://github.com/leew0nseok/network-study/assets/101381258/efdb32b0-55a3-4386-a0da-41b3284929cc">


정답: c

호스트 기반 방화벽은 컴퓨터의 방화벽처럼 최종 호스트에서 실행되는 소프트웨어이다. b와 d는 실제 방화벽 유형이 아님. 

# Packet Tracer Introduction | Lab

패킷 트레이서 실습 프로그램으로 위의 이미지를 구현하면 아래와 같이 된다.
<img width="1261" alt="Untitled 15" src="https://github.com/leew0nseok/network-study/assets/101381258/72a78987-8e1a-4572-9c60-74958d4b62ac">

