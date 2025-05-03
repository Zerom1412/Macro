# 🏪 Macro
<div align="center">
    <!-- Banner -->
    <div style="
      width: 100%;
      height: 200px;
      background-color: #d0e8ff;
      border-radius: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      font-weight: 900;
      color: #005b99;
      line-height: 1.4;
      text-align: center;
    ">
      <div>Smart Order Prediction System</div>
      <div>of Unattended Store</div>
      <div style="margin-top: 6px;">무인가게 스마트 재고 예측 시스템</div>
    </div>
    <br>
    <!-- Badges -->
    <div style="
      display: flex;
      gap: 10px;
      justify-content: center;
      flex-wrap: wrap;
    ">
      <img src="https://img.shields.io/badge/Dart-Flutter-blue" alt="Dart Flutter badge">
      <img src="https://img.shields.io/badge/FastAPI-Python-green" alt="FastAPI Python badge">
      <img src="https://img.shields.io/badge/MySQL-Database-orange" alt="MySQL badge">
    </div>
</div>



## Project OverView
A system for unattended small retail stores that predicts inventory and recommends orders automatically based on daily sales data.

무인으로 운영되는 소형 상점에서, 매일의 판매 데이터를 기반으로 상품별 재고 예측 및 자동 발주 추천을 수행하는 시스템입니다.

## System Roadmap
1. 📦 데이터 준비 / Data Preparation
    - DB 테이블 설계
      - [x] 상품 ( Products )
      - [x] 판매 ( Sales )
      - [ ] 날짜 ( Dates )
      - [ ] 재고 ( Stocks )

2. 📊 데이터베이스 구축 / Database Setup
    - 관계형 DB
      - [ ] 상품 ( Products )
      - Barcode
      - Brand
      - Name
      - Category
      - Provider
      - PagcakeSize
      - MinQuantity
      - Stars
      - [ ] 날짜 ( Dates )
      - Date
      - IsSpecialDay
    - 시계열 DB
      - [ ] 판매 ( Sales )
      * Barcode ( Products )
      * Weekend
      * IsSpecialDay
      * SaleQuantity
