# 자바 ORM 표준 JPA 프로그래밍
## [1장 JPA 소개](https://github.com/Limhyeonsu/jpa/blob/main/01.JPA%20%EC%86%8C%EA%B0%9C.md)
* SQL을 직접 다룰 때 발생하는 문제점
* 패러다임의 불일치
* JPA란 무엇인가?

## [2장 JPA 시작](https://github.com/Limhyeonsu/jpa/blob/main/02.JPA%EC%8B%9C%EC%9E%91.md)
* 이클립스 설치와 프로젝트 불러오기
* H2 데이터베이스 설치
* 라이브러리와 프로젝트 구조
* 객체 매핑 시작
* persistence.xml 설정
* 애플리케이션 개발

## [3장 영속성 관리](https://github.com/Limhyeonsu/jpa/blob/main/03.%EC%98%81%EC%86%8D%EC%84%B1%20%EA%B4%80%EB%A6%AC.md)
* 엔티티 매니저 팩토리와 엔티티 매니저
* 영속성 컨텍스트란?
* 엔티티의 생명주기
* 영속성 컨텍스트의 특징
* 플러시
* 준영속

## [4장 엔티티 매핑](https://github.com/Limhyeonsu/jpa/blob/main/04.%EC%97%94%ED%8B%B0%ED%8B%B0%EB%A7%A4%ED%95%91.md)
* @Entity
* @Table
* 다양한 매핑 사용
* 데이터베이스 스키마 자동 생성
* DDL 생성 기능
* 기본 키 매핑
* 필드와 컬럼 매핑:레퍼런스

## [5장 연관관계 매핑 기초](https://github.com/Limhyeonsu/jpa/blob/main/05.%EC%97%B0%EA%B4%80%EA%B4%80%EA%B3%84%20%EB%A7%A4%ED%95%91%20%EA%B8%B0%EC%B4%88.md)
* 단방향 연관관계
* 연관관계 사용
* 양방향 연관관계
* 연관관계의 주인
* 양방향 연관관계 저장
* 양방향 연관관계의 주의점

## [6장 다양한 연관관계 매핑](https://github.com/Limhyeonsu/jpa/blob/main/06.%EB%8B%A4%EC%96%91%ED%95%9C%20%EC%97%B0%EA%B4%80%EA%B4%80%EA%B3%84%20%EB%A7%A4%ED%95%91.md)
* 다대일 (N:1)
* 일대다 (1:N)
* 일대일 (1:1)
* 다대다 (N:N)

## [7장 고급 매핑](https://github.com/Limhyeonsu/jpa/blob/main/07.%EA%B3%A0%EA%B8%89%20%EB%A7%A4%ED%95%91.md)
* 상속 관계 매핑
* @MappedSuperclass
* 복합 키와 식별 관계 매핑
* 조인 테이블
* 엔티티 하나에 여러 테이블 매핑

## [8장 프록시와 연관관계 관리](https://github.com/Limhyeonsu/jpa/blob/main/08.%ED%94%84%EB%A1%9D%EC%8B%9C%EC%99%80%20%EC%97%B0%EA%B4%80%EA%B4%80%EA%B3%84%20%EA%B4%80%EB%A6%AC.md)
* 프록시
* 즉시 로딩과 지연 로딩
* 지연 로딩 활용
* 영속성 전이 : CASCADE
* 고아 객체
* 영속성 전이 + 고아 객체, 생명주기

## [9장 값 타입](https://github.com/Limhyeonsu/jpa/blob/main/09.%EA%B0%92%20%ED%83%80%EC%9E%85.md)
* 기본값 타입
* 임베디드 타입(복합 값 타입)
* 값 타입과 불변 객체
* 값 타입의 비교
* 값 타입 컬렉션

## 10장 객체지향 쿼리 언어
* 객체지향 쿼리 소개
* JPQL
* Criteria
* QueryDSL
* 네이티브 SQL
* 객체지향 쿼리 심화

## 11장 웹 애플리케이션 제작
* 프로젝트 환경설정
* 도메인 모델과 테이블 설계
* 애플리케이션 구현

## 12장 스프링 데이터 JPA
* 스프링 데이터 JPA 소개
* 스프링 데이터 JPA 설정
* 공통 인터페이스 기능
* 쿼리 메소드 기능
* 명세
* 사용자 정의 리포지토리 구현
* Web 확장
* 스프링 데이터 JPA가 사용하는 구현체
* JPA 샵에 적용
* 스프링 데이터 JPA와 QueryDSL 통합

## 13장 웹 애플리케이션과 영속성 관리
* 트랜잭션 범위의 영속성 컨텍스트
* 준영속 상태와 지연 로딩
* OSIV
* 너무 엄격한 계층

## 14장 컬렉션과 부가 기능
* 컬렉션
* @Converter
* 리스너
* 엔티티 그래프

## 15장 고급 주제와 성능 최적화
* 예외 처리
* 엔티티 비교
* 프록시 심화 주제
* 성능 최적화

## 16장 트랜잭션과 락, 2차 캐시
* 트랜잭션과 락
* 2차 캐시