# RFP（提案依頼書）
<a id="markdown-rfp%EF%BC%88%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E6%9B%B8%EF%BC%89" name="rfp%EF%BC%88%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E6%9B%B8%EF%BC%89"></a>

---

<!-- TOC -->

- [RFP（提案依頼書）](#rfp%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E6%9B%B8)
- [プロジェクト概要](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%A6%82%E8%A6%81)
    - [プロジェクトの背景](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E8%83%8C%E6%99%AF)
        - [事業計画概要](#%E4%BA%8B%E6%A5%AD%E8%A8%88%E7%94%BB%E6%A6%82%E8%A6%81)
        - [システム全体図](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3)
        - [中長期システム戦略概要](#%E4%B8%AD%E9%95%B7%E6%9C%9F%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%88%A6%E7%95%A5%E6%A6%82%E8%A6%81)
    - [プロジェクトの目的](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84)
        - [プロジェクトの目的](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84)
        - [課題・解決策へのアプローチ](#%E8%AA%B2%E9%A1%8C%E3%83%BB%E8%A7%A3%E6%B1%BA%E7%AD%96%E3%81%B8%E3%81%AE%E3%82%A2%E3%83%97%E3%83%AD%E3%83%BC%E3%83%81)
    - [プロジェクトの前提条件](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E5%89%8D%E6%8F%90%E6%9D%A1%E4%BB%B6)
        - [プロジェクトのQCD目標](#%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AEqcd%E7%9B%AE%E6%A8%99)
            - [品質（Q）](#%E5%93%81%E8%B3%AAq)
            - [費用（C）](#%E8%B2%BB%E7%94%A8c)
            - [期限（D）](#%E6%9C%9F%E9%99%90d)
        - [マスタースケジュールと提案依頼範囲](#%E3%83%9E%E3%82%B9%E3%82%BF%E3%83%BC%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB%E3%81%A8%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E7%AF%84%E5%9B%B2)
- [業務・システム概要](#%E6%A5%AD%E5%8B%99%E3%83%BB%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81)
    - [システム概要](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81)
        - [システム全体図](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3)
        - [システム化機能一覧](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%A9%9F%E8%83%BD%E4%B8%80%E8%A6%A7)
        - [他システムへの影響](#%E4%BB%96%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%B8%E3%81%AE%E5%BD%B1%E9%9F%BF)
            - [事業全体のシステム化戦略、計画との整合性](#%E4%BA%8B%E6%A5%AD%E5%85%A8%E4%BD%93%E3%81%AE%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%88%A6%E7%95%A5%E8%A8%88%E7%94%BB%E3%81%A8%E3%81%AE%E6%95%B4%E5%90%88%E6%80%A7)
            - [システム関連項目の検討状況](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%A2%E9%80%A3%E9%A0%85%E7%9B%AE%E3%81%AE%E6%A4%9C%E8%A8%8E%E7%8A%B6%E6%B3%81)
        - [既存システム流用検討結果](#%E6%97%A2%E5%AD%98%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%B5%81%E7%94%A8%E6%A4%9C%E8%A8%8E%E7%B5%90%E6%9E%9C)
        - [インフラ構成概要図](#%E3%82%A4%E3%83%B3%E3%83%95%E3%83%A9%E6%A7%8B%E6%88%90%E6%A6%82%E8%A6%81%E5%9B%B3)
        - [システムの使用者](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%AE%E4%BD%BF%E7%94%A8%E8%80%85)
    - [業務の概要](#%E6%A5%AD%E5%8B%99%E3%81%AE%E6%A6%82%E8%A6%81)
        - [業務概要](#%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81)
        - [業務概要図](#%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81%E5%9B%B3)
        - [現状業務フロー](#%E7%8F%BE%E7%8A%B6%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC)
        - [新業務フロー](#%E6%96%B0%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC)
        - [サービスレベル想定](#%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%83%AC%E3%83%99%E3%83%AB%E6%83%B3%E5%AE%9A)
        - [信頼性](#%E4%BF%A1%E9%A0%BC%E6%80%A7)
            - [効率性](#%E5%8A%B9%E7%8E%87%E6%80%A7)
        - [保守性](#%E4%BF%9D%E5%AE%88%E6%80%A7)
        - [付帯作業](#%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD)
        - [セキュリティ](#%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3)
- [機能要件](#%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6)
    - [機能要件（プロセス）](#%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%E3%83%97%E3%83%AD%E3%82%BB%E3%82%B9)
        - [機能情報関連図](#%E6%A9%9F%E8%83%BD%E6%83%85%E5%A0%B1%E9%96%A2%E9%80%A3%E5%9B%B3)
        - [業務流れ図](#%E6%A5%AD%E5%8B%99%E6%B5%81%E3%82%8C%E5%9B%B3)
        - [業務処理定義書](#%E6%A5%AD%E5%8B%99%E5%87%A6%E7%90%86%E5%AE%9A%E7%BE%A9%E6%9B%B8)
        - [システム機能階層図](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A9%9F%E8%83%BD%E9%9A%8E%E5%B1%A4%E5%9B%B3)
    - [機能要件（データ）](#%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%E3%83%87%E3%83%BC%E3%82%BF)
        - [概念ER図](#%E6%A6%82%E5%BF%B5er%E5%9B%B3)
        - [データ項目定義書](#%E3%83%87%E3%83%BC%E3%82%BF%E9%A0%85%E7%9B%AE%E5%AE%9A%E7%BE%A9%E6%9B%B8)
    - [機能要件（インターフェース）](#%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)
        - [システム間関連図](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E9%96%A2%E9%80%A3%E5%9B%B3)
        - [システム間インタフェース定義書](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9%E5%AE%9A%E7%BE%A9%E6%9B%B8)
        - [画面・帳票一覧](#%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E4%B8%80%E8%A6%A7)
        - [画面・帳票レイアウト](#%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6%E3%83%88)
- [非機能要件](#%E9%9D%9E%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6)
    - [品質要件](#%E5%93%81%E8%B3%AA%E8%A6%81%E4%BB%B6)
        - [機能性](#%E6%A9%9F%E8%83%BD%E6%80%A7)
        - [信頼性](#%E4%BF%A1%E9%A0%BC%E6%80%A7)
        - [使用性](#%E4%BD%BF%E7%94%A8%E6%80%A7)
        - [効率性](#%E5%8A%B9%E7%8E%87%E6%80%A7)
        - [保守性](#%E4%BF%9D%E5%AE%88%E6%80%A7)
        - [移植性](#%E7%A7%BB%E6%A4%8D%E6%80%A7)
    - [技術要件](#%E6%8A%80%E8%A1%93%E8%A6%81%E4%BB%B6)
    - [運用・操作要件](#%E9%81%8B%E7%94%A8%E3%83%BB%E6%93%8D%E4%BD%9C%E8%A6%81%E4%BB%B6)
    - [移行要件](#%E7%A7%BB%E8%A1%8C%E8%A6%81%E4%BB%B6)
    - [付帯作業](#%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD)
    - [セキュリティ](#%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3)
- [開発条件](#%E9%96%8B%E7%99%BA%E6%9D%A1%E4%BB%B6)
    - [開発の特徴](#%E9%96%8B%E7%99%BA%E3%81%AE%E7%89%B9%E5%BE%B4)
    - [開発工数見積](#%E9%96%8B%E7%99%BA%E5%B7%A5%E6%95%B0%E8%A6%8B%E7%A9%8D)
    - [開発期間](#%E9%96%8B%E7%99%BA%E6%9C%9F%E9%96%93)
    - [作業場所](#%E4%BD%9C%E6%A5%AD%E5%A0%B4%E6%89%80)
    - [開発用コンピュータ機器・使用材料の負担](#%E9%96%8B%E7%99%BA%E7%94%A8%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E6%A9%9F%E5%99%A8%E3%83%BB%E4%BD%BF%E7%94%A8%E6%9D%90%E6%96%99%E3%81%AE%E8%B2%A0%E6%8B%85)
    - [貸与物件・資料](#%E8%B2%B8%E4%B8%8E%E7%89%A9%E4%BB%B6%E3%83%BB%E8%B3%87%E6%96%99)
    - [納品条件](#%E7%B4%8D%E5%93%81%E6%9D%A1%E4%BB%B6)
        - [納品物一覧](#%E7%B4%8D%E5%93%81%E7%89%A9%E4%B8%80%E8%A6%A7)
        - [納品方法](#%E7%B4%8D%E5%93%81%E6%96%B9%E6%B3%95)
- [提案依頼事項](#%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E4%BA%8B%E9%A0%85)
    - [システム全体概要](#%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E6%A6%82%E8%A6%81)
    - [提供機能と実現化方式](#%E6%8F%90%E4%BE%9B%E6%A9%9F%E8%83%BD%E3%81%A8%E5%AE%9F%E7%8F%BE%E5%8C%96%E6%96%B9%E5%BC%8F)
    - [運用条件](#%E9%81%8B%E7%94%A8%E6%9D%A1%E4%BB%B6)
    - [開発体制](#%E9%96%8B%E7%99%BA%E4%BD%93%E5%88%B6)
    - [開発スケジュール](#%E9%96%8B%E7%99%BA%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)
    - [定例報告およびレビュー](#%E5%AE%9A%E4%BE%8B%E5%A0%B1%E5%91%8A%E3%81%8A%E3%82%88%E3%81%B3%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC)
    - [開発管理・開発手法・開発言語](#%E9%96%8B%E7%99%BA%E7%AE%A1%E7%90%86%E3%83%BB%E9%96%8B%E7%99%BA%E6%89%8B%E6%B3%95%E3%83%BB%E9%96%8B%E7%99%BA%E8%A8%80%E8%AA%9E)
    - [費用](#%E8%B2%BB%E7%94%A8)
        - [貴社情報](#%E8%B2%B4%E7%A4%BE%E6%83%85%E5%A0%B1)
        - [貴社問い合わせ窓口](#%E8%B2%B4%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3)
- [提案手続き](#%E6%8F%90%E6%A1%88%E6%89%8B%E7%B6%9A%E3%81%8D)
    - [参加資格条件](#%E5%8F%82%E5%8A%A0%E8%B3%87%E6%A0%BC%E6%9D%A1%E4%BB%B6)
    - [提案スケジュール](#%E6%8F%90%E6%A1%88%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)
    - [RFP説明会・質問会](#rfp%E8%AA%AC%E6%98%8E%E4%BC%9A%E3%83%BB%E8%B3%AA%E5%95%8F%E4%BC%9A)
    - [質問期限](#%E8%B3%AA%E5%95%8F%E6%9C%9F%E9%99%90)
    - [提案書の提出](#%E6%8F%90%E6%A1%88%E6%9B%B8%E3%81%AE%E6%8F%90%E5%87%BA)
    - [プレゼンテーション](#%E3%83%97%E3%83%AC%E3%82%BC%E3%83%B3%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
    - [選定結果の連絡](#%E9%81%B8%E5%AE%9A%E7%B5%90%E6%9E%9C%E3%81%AE%E9%80%A3%E7%B5%A1)
    - [弊社問い合わせ窓口](#%E5%BC%8A%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3)
- [評価](#%E8%A9%95%E4%BE%A1)
    - [評価の方針](#%E8%A9%95%E4%BE%A1%E3%81%AE%E6%96%B9%E9%87%9D)
    - [評価項目](#%E8%A9%95%E4%BE%A1%E9%A0%85%E7%9B%AE)
- [契約事項](#%E5%A5%91%E7%B4%84%E4%BA%8B%E9%A0%85)
    - [発注形態](#%E7%99%BA%E6%B3%A8%E5%BD%A2%E6%85%8B)
    - [再委託](#%E5%86%8D%E5%A7%94%E8%A8%97)
    - [検収](#%E6%A4%9C%E5%8F%8E)
        - [検収・検査期間について](#%E6%A4%9C%E5%8F%8E%E3%83%BB%E6%A4%9C%E6%9F%BB%E6%9C%9F%E9%96%93%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
        - [作業完了報告書提出年月日について](#%E4%BD%9C%E6%A5%AD%E5%AE%8C%E4%BA%86%E5%A0%B1%E5%91%8A%E6%9B%B8%E6%8F%90%E5%87%BA%E5%B9%B4%E6%9C%88%E6%97%A5%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
    - [支払条件](#%E6%94%AF%E6%89%95%E6%9D%A1%E4%BB%B6)
    - [機密保持契約](#%E6%A9%9F%E5%AF%86%E4%BF%9D%E6%8C%81%E5%A5%91%E7%B4%84)
    - [著作権等](#%E8%91%97%E4%BD%9C%E6%A8%A9%E7%AD%89)
    - [瑕疵担保・賠償責任](#%E7%91%95%E7%96%B5%E6%8B%85%E4%BF%9D%E3%83%BB%E8%B3%A0%E5%84%9F%E8%B2%AC%E4%BB%BB)
    - [その他](#%E3%81%9D%E3%81%AE%E4%BB%96)
- [別紙](#%E5%88%A5%E7%B4%99)
    - [質問票](#%E8%B3%AA%E5%95%8F%E7%A5%A8)

<!-- /TOC -->

---

# プロジェクト概要
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%A6%82%E8%A6%81" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%A6%82%E8%A6%81"></a>

## プロジェクトの背景
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E8%83%8C%E6%99%AF" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E8%83%8C%E6%99%AF"></a>

### 事業計画概要
<a id="markdown-%E4%BA%8B%E6%A5%AD%E8%A8%88%E7%94%BB%E6%A6%82%E8%A6%81" name="%E4%BA%8B%E6%A5%AD%E8%A8%88%E7%94%BB%E6%A6%82%E8%A6%81"></a>

事業計画と本プロジェクトの関係性…。

### システム全体図
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3"></a>

システム全体のうち、本プロジェクトの対象とする範囲を図示…。

### 中長期システム戦略概要
<a id="markdown-%E4%B8%AD%E9%95%B7%E6%9C%9F%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%88%A6%E7%95%A5%E6%A6%82%E8%A6%81" name="%E4%B8%AD%E9%95%B7%E6%9C%9F%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%88%A6%E7%95%A5%E6%A6%82%E8%A6%81"></a>

As-Is To-Be の比較および、それらのうち、本プロジェクトの対象とする範囲を図示…。

## プロジェクトの目的
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84"></a>

### プロジェクトの目的
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%9B%AE%E7%9A%84"></a>

本プロジェクトの目的…。

### 課題・解決策へのアプローチ
<a id="markdown-%E8%AA%B2%E9%A1%8C%E3%83%BB%E8%A7%A3%E6%B1%BA%E7%AD%96%E3%81%B8%E3%81%AE%E3%82%A2%E3%83%97%E3%83%AD%E3%83%BC%E3%83%81" name="%E8%AA%B2%E9%A1%8C%E3%83%BB%E8%A7%A3%E6%B1%BA%E7%AD%96%E3%81%B8%E3%81%AE%E3%82%A2%E3%83%97%E3%83%AD%E3%83%BC%E3%83%81"></a>

| プロジェクトの課題                                         |
| ---------------------------------------------------------- |
| 活動状況を必要な人が必要なときに把握できなければならない。 |

| ブレイクダウンされた課題 | 解決策のオプション         | 解決策のメリット／デメリット              | 解決策の選択理由 |
| ------------------------ | -------------------------- | ----------------------------------------- | ---------------- |
| (1)XXXXXが困難           | (1-1)XXXXXを導入する       | ○XXXXXができるようになる<br>●できなくなる | XXXXXのため      |
|                          | (1-2)XXXXXできるようにする | ○XXXXXができるようになる<br>●できなくなる | XXXXXのため      |
| (2)XXXXXが困難           | (2-1)XXXXXを導入する       | ○XXXXXができるようになる<br>●できなくなる | XXXXXのため      |
|                          | (2-2)XXXXXできるようにする | ○XXXXXができるようになる<br>●できなくなる | XXXXXのため      |

| 備考                    |
| ----------------------- |
| ○:メリット ●:デメリット |

## プロジェクトの前提条件
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E5%89%8D%E6%8F%90%E6%9D%A1%E4%BB%B6" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E5%89%8D%E6%8F%90%E6%9D%A1%E4%BB%B6"></a>

### プロジェクトのQCD目標
<a id="markdown-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AEqcd%E7%9B%AE%E6%A8%99" name="%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AEqcd%E7%9B%AE%E6%A8%99"></a>

#### 品質（Q）
<a id="markdown-%E5%93%81%E8%B3%AA%EF%BC%88q%EF%BC%89" name="%E5%93%81%E8%B3%AA%EF%BC%88q%EF%BC%89"></a>

品質要件を列挙…。

#### 費用（C）
<a id="markdown-%E8%B2%BB%E7%94%A8%EF%BC%88c%EF%BC%89" name="%E8%B2%BB%E7%94%A8%EF%BC%88c%EF%BC%89"></a>

予算はXXX,XXX円（これを超過する場合は理由を明記すること。予算の上乗せの可能性あり）

#### 期限（D）
<a id="markdown-%E6%9C%9F%E9%99%90%EF%BC%88d%EF%BC%89" name="%E6%9C%9F%E9%99%90%EF%BC%88d%EF%BC%89"></a>

プロジェクト期間は、YYYY年MM月DD日からYYYY年MM月DD日とする…。

本番稼働開始日は、YYYY年MM月DD日とする…。

### マスタースケジュールと提案依頼範囲
<a id="markdown-%E3%83%9E%E3%82%B9%E3%82%BF%E3%83%BC%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB%E3%81%A8%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E7%AF%84%E5%9B%B2" name="%E3%83%9E%E3%82%B9%E3%82%BF%E3%83%BC%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB%E3%81%A8%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E7%AF%84%E5%9B%B2"></a>

<img src="plantuml/マスタースケジュールと提案依頼範囲.png">

# 業務・システム概要
<a id="markdown-%E6%A5%AD%E5%8B%99%E3%83%BB%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81" name="%E6%A5%AD%E5%8B%99%E3%83%BB%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81"></a>

## システム概要
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A6%82%E8%A6%81"></a>

本プロジェクトの対象とする範囲の概要…。

### システム全体図
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E5%9B%B3"></a>

システム全体のうち、本プロジェクトの対象とする範囲を図示…。

### システム化機能一覧
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%A9%9F%E8%83%BD%E4%B8%80%E8%A6%A7" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%A9%9F%E8%83%BD%E4%B8%80%E8%A6%A7"></a>

| システム化機能（大項目）                          | システム化機能（中項目） |
| ------------------------------------------------- | ------------------------ |
| (1)データを一元管理し、オンラインで参照可能とする | (1-1)情報管理機能        |
|                                                   | (1-2)情報検索機能        |
| (2)                                               | (2-1)                    |
|                                                   | (2-2)                    |

### 他システムへの影響
<a id="markdown-%E4%BB%96%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%B8%E3%81%AE%E5%BD%B1%E9%9F%BF" name="%E4%BB%96%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%B8%E3%81%AE%E5%BD%B1%E9%9F%BF"></a>

他システムへの影響評価を列挙…。

#### 事業全体のシステム化戦略、計画との整合性
<a id="markdown-%E4%BA%8B%E6%A5%AD%E5%85%A8%E4%BD%93%E3%81%AE%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%88%A6%E7%95%A5%E3%80%81%E8%A8%88%E7%94%BB%E3%81%A8%E3%81%AE%E6%95%B4%E5%90%88%E6%80%A7" name="%E4%BA%8B%E6%A5%AD%E5%85%A8%E4%BD%93%E3%81%AE%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%8C%96%E6%88%A6%E7%95%A5%E3%80%81%E8%A8%88%E7%94%BB%E3%81%A8%E3%81%AE%E6%95%B4%E5%90%88%E6%80%A7"></a>

| 対象項目                | 検討内容の評価                |
| ----------------------- | ----------------------------- |
| (1)中長期システム化戦略 | 他プロジェクトとの整合性…。   |
| (2)新規システム化計画   | 新規システム開発との整合性…。 |
| (3)既存システム改修計画 | 既存システム改修との整合性…。 |

#### システム関連項目の検討状況
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%A2%E9%80%A3%E9%A0%85%E7%9B%AE%E3%81%AE%E6%A4%9C%E8%A8%8E%E7%8A%B6%E6%B3%81" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%A2%E9%80%A3%E9%A0%85%E7%9B%AE%E3%81%AE%E6%A4%9C%E8%A8%8E%E7%8A%B6%E6%B3%81"></a>

| 対象ドキュメント                  | 検討内容の評価              |
| --------------------------------- | --------------------------- |
| (1)他システムへの影響             | 既存システムへの影響範囲…。 |
| (2)新システムで代替されるシステム | 旧システムは廃棄処分とする  |

### 既存システム流用検討結果
<a id="markdown-%E6%97%A2%E5%AD%98%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%B5%81%E7%94%A8%E6%A4%9C%E8%A8%8E%E7%B5%90%E6%9E%9C" name="%E6%97%A2%E5%AD%98%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%B5%81%E7%94%A8%E6%A4%9C%E8%A8%8E%E7%B5%90%E6%9E%9C"></a>

| 対象システム   | 検討内容の評価 |
| -------------- | -------------- |
| (1)XXXシステム |                |

### インフラ構成概要図
<a id="markdown-%E3%82%A4%E3%83%B3%E3%83%95%E3%83%A9%E6%A7%8B%E6%88%90%E6%A6%82%E8%A6%81%E5%9B%B3" name="%E3%82%A4%E3%83%B3%E3%83%95%E3%83%A9%E6%A7%8B%E6%88%90%E6%A6%82%E8%A6%81%E5%9B%B3"></a>

ネットワーク、サーバー等の構成を図示…。

### システムの使用者
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%AE%E4%BD%BF%E7%94%A8%E8%80%85" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E3%81%AE%E4%BD%BF%E7%94%A8%E8%80%85"></a>

システムを使用するユーザーの種別や役割を列挙…。システム内でアクセス制御や権限管理を行う場合は組織図も記載。店舗／支店の規模によっては地方毎・都道府県毎の店舗数も記載した方が良い（遠方だと導入費用が割高になる）。

## 業務の概要
<a id="markdown-%E6%A5%AD%E5%8B%99%E3%81%AE%E6%A6%82%E8%A6%81" name="%E6%A5%AD%E5%8B%99%E3%81%AE%E6%A6%82%E8%A6%81"></a>

### 業務概要
<a id="markdown-%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81" name="%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81"></a>

### 業務概要図
<a id="markdown-%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81%E5%9B%B3" name="%E6%A5%AD%E5%8B%99%E6%A6%82%E8%A6%81%E5%9B%B3"></a>

<img src="plantuml/業務概要図.png">

### 現状業務フロー
<a id="markdown-%E7%8F%BE%E7%8A%B6%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC" name="%E7%8F%BE%E7%8A%B6%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC"></a>

### 新業務フロー
<a id="markdown-%E6%96%B0%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC" name="%E6%96%B0%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC"></a>

### サービスレベル想定
<a id="markdown-%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%83%AC%E3%83%99%E3%83%AB%E6%83%B3%E5%AE%9A" name="%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%83%AC%E3%83%99%E3%83%AB%E6%83%B3%E5%AE%9A"></a>

勤務時間、営業時間、夜間バッチ処理の想定実行タイミング、サポート時間を列挙…。

### 信頼性
<a id="markdown-%E4%BF%A1%E9%A0%BC%E6%80%A7" name="%E4%BF%A1%E9%A0%BC%E6%80%A7"></a>

システム改修、メンテナンスのための計画停止の可能性、その頻度や停止期間の上限。

#### 効率性
<a id="markdown-%E5%8A%B9%E7%8E%87%E6%80%A7" name="%E5%8A%B9%E7%8E%87%E6%80%A7"></a>

応答速度、同時接続数、バッチ処理のデータ量等の上限。

### 保守性
<a id="markdown-%E4%BF%9D%E5%AE%88%E6%80%A7" name="%E4%BF%9D%E5%AE%88%E6%80%A7"></a>

保守の容易さを考慮した開発。

### 付帯作業
<a id="markdown-%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD" name="%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD"></a>

システム管理者・利用者・メンテナンス用のマニュアルの作成。

### セキュリティ
<a id="markdown-%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3" name="%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3"></a>

アクセスコントロール（ユーザー種別ごと）、ログ、認証、セキュリティポリシーや社内規定への準拠。

# 機能要件
<a id="markdown-%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6" name="%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6"></a>

## 機能要件（プロセス）
<a id="markdown-%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%83%97%E3%83%AD%E3%82%BB%E3%82%B9%EF%BC%89" name="%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%83%97%E3%83%AD%E3%82%BB%E3%82%B9%EF%BC%89"></a>

### 機能情報関連図
<a id="markdown-%E6%A9%9F%E8%83%BD%E6%83%85%E5%A0%B1%E9%96%A2%E9%80%A3%E5%9B%B3" name="%E6%A9%9F%E8%83%BD%E6%83%85%E5%A0%B1%E9%96%A2%E9%80%A3%E5%9B%B3"></a>

### 業務流れ図
<a id="markdown-%E6%A5%AD%E5%8B%99%E6%B5%81%E3%82%8C%E5%9B%B3" name="%E6%A5%AD%E5%8B%99%E6%B5%81%E3%82%8C%E5%9B%B3"></a>

### 業務処理定義書
<a id="markdown-%E6%A5%AD%E5%8B%99%E5%87%A6%E7%90%86%E5%AE%9A%E7%BE%A9%E6%9B%B8" name="%E6%A5%AD%E5%8B%99%E5%87%A6%E7%90%86%E5%AE%9A%E7%BE%A9%E6%9B%B8"></a>

### システム機能階層図
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A9%9F%E8%83%BD%E9%9A%8E%E5%B1%A4%E5%9B%B3" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E6%A9%9F%E8%83%BD%E9%9A%8E%E5%B1%A4%E5%9B%B3"></a>

## 機能要件（データ）
<a id="markdown-%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%83%87%E3%83%BC%E3%82%BF%EF%BC%89" name="%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%83%87%E3%83%BC%E3%82%BF%EF%BC%89"></a>

### 概念ER図
<a id="markdown-%E6%A6%82%E5%BF%B5er%E5%9B%B3" name="%E6%A6%82%E5%BF%B5er%E5%9B%B3"></a>

### データ項目定義書
<a id="markdown-%E3%83%87%E3%83%BC%E3%82%BF%E9%A0%85%E7%9B%AE%E5%AE%9A%E7%BE%A9%E6%9B%B8" name="%E3%83%87%E3%83%BC%E3%82%BF%E9%A0%85%E7%9B%AE%E5%AE%9A%E7%BE%A9%E6%9B%B8"></a>

## 機能要件（インターフェース）
<a id="markdown-%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9%EF%BC%89" name="%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6%EF%BC%88%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9%EF%BC%89"></a>

### システム間関連図
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E9%96%A2%E9%80%A3%E5%9B%B3" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E9%96%A2%E9%80%A3%E5%9B%B3"></a>

### システム間インタフェース定義書
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9%E5%AE%9A%E7%BE%A9%E6%9B%B8" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%93%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9%E5%AE%9A%E7%BE%A9%E6%9B%B8"></a>

### 画面・帳票一覧
<a id="markdown-%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E4%B8%80%E8%A6%A7" name="%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E4%B8%80%E8%A6%A7"></a>

画面・帳票の、名称、目的、用途、利用者等を列挙…。

### 画面・帳票レイアウト
<a id="markdown-%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6%E3%83%88" name="%E7%94%BB%E9%9D%A2%E3%83%BB%E5%B8%B3%E7%A5%A8%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6%E3%83%88"></a>

画面・帳票ごとの、名称、入力データ、出力データを列挙…。

# 非機能要件
<a id="markdown-%E9%9D%9E%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6" name="%E9%9D%9E%E6%A9%9F%E8%83%BD%E8%A6%81%E4%BB%B6"></a>

## 品質要件
<a id="markdown-%E5%93%81%E8%B3%AA%E8%A6%81%E4%BB%B6" name="%E5%93%81%E8%B3%AA%E8%A6%81%E4%BB%B6"></a>

### 機能性
<a id="markdown-%E6%A9%9F%E8%83%BD%E6%80%A7" name="%E6%A9%9F%E8%83%BD%E6%80%A7"></a>

総合テストの際のバグ密度の目標値。

### 信頼性
<a id="markdown-%E4%BF%A1%E9%A0%BC%E6%80%A7" name="%E4%BF%A1%E9%A0%BC%E6%80%A7"></a>

サービスレベル想定を参照。

### 使用性
<a id="markdown-%E4%BD%BF%E7%94%A8%E6%80%A7" name="%E4%BD%BF%E7%94%A8%E6%80%A7"></a>

UXを考慮した画面とすること。

既存システムとの統一性を持たせること。

### 効率性
<a id="markdown-%E5%8A%B9%E7%8E%87%E6%80%A7" name="%E5%8A%B9%E7%8E%87%E6%80%A7"></a>

サービスレベル想定を参照。

### 保守性
<a id="markdown-%E4%BF%9D%E5%AE%88%E6%80%A7" name="%E4%BF%9D%E5%AE%88%E6%80%A7"></a>

サービスレベル想定を参照。

### 移植性
<a id="markdown-%E7%A7%BB%E6%A4%8D%E6%80%A7" name="%E7%A7%BB%E6%A4%8D%E6%80%A7"></a>

ほかのシステムへの移植性を考慮した開発。

## 技術要件
<a id="markdown-%E6%8A%80%E8%A1%93%E8%A6%81%E4%BB%B6" name="%E6%8A%80%E8%A1%93%E8%A6%81%E4%BB%B6"></a>

開発言語やフレームワーク。

## 運用・操作要件
<a id="markdown-%E9%81%8B%E7%94%A8%E3%83%BB%E6%93%8D%E4%BD%9C%E8%A6%81%E4%BB%B6" name="%E9%81%8B%E7%94%A8%E3%83%BB%E6%93%8D%E4%BD%9C%E8%A6%81%E4%BB%B6"></a>

## 移行要件
<a id="markdown-%E7%A7%BB%E8%A1%8C%E8%A6%81%E4%BB%B6" name="%E7%A7%BB%E8%A1%8C%E8%A6%81%E4%BB%B6"></a>

## 付帯作業
<a id="markdown-%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD" name="%E4%BB%98%E5%B8%AF%E4%BD%9C%E6%A5%AD"></a>

サービスレベル想定を参照。

## セキュリティ
<a id="markdown-%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3" name="%E3%82%BB%E3%82%AD%E3%83%A5%E3%83%AA%E3%83%86%E3%82%A3"></a>

サービスレベル想定を参照。

# 開発条件
<a id="markdown-%E9%96%8B%E7%99%BA%E6%9D%A1%E4%BB%B6" name="%E9%96%8B%E7%99%BA%E6%9D%A1%E4%BB%B6"></a>

## 開発の特徴
<a id="markdown-%E9%96%8B%E7%99%BA%E3%81%AE%E7%89%B9%E5%BE%B4" name="%E9%96%8B%E7%99%BA%E3%81%AE%E7%89%B9%E5%BE%B4"></a>

開発言語やフレームワーク。

## 開発工数見積
<a id="markdown-%E9%96%8B%E7%99%BA%E5%B7%A5%E6%95%B0%E8%A6%8B%E7%A9%8D" name="%E9%96%8B%E7%99%BA%E5%B7%A5%E6%95%B0%E8%A6%8B%E7%A9%8D"></a>

## 開発期間
<a id="markdown-%E9%96%8B%E7%99%BA%E6%9C%9F%E9%96%93" name="%E9%96%8B%E7%99%BA%E6%9C%9F%E9%96%93"></a>

開発期間は、YYYY年MM月DD日からYYYY年MM月DD日とする…。

## 作業場所
<a id="markdown-%E4%BD%9C%E6%A5%AD%E5%A0%B4%E6%89%80" name="%E4%BD%9C%E6%A5%AD%E5%A0%B4%E6%89%80"></a>

弊社XXX会議室

貴社事務所

## 開発用コンピュータ機器・使用材料の負担
<a id="markdown-%E9%96%8B%E7%99%BA%E7%94%A8%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E6%A9%9F%E5%99%A8%E3%83%BB%E4%BD%BF%E7%94%A8%E6%9D%90%E6%96%99%E3%81%AE%E8%B2%A0%E6%8B%85" name="%E9%96%8B%E7%99%BA%E7%94%A8%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E6%A9%9F%E5%99%A8%E3%83%BB%E4%BD%BF%E7%94%A8%E6%9D%90%E6%96%99%E3%81%AE%E8%B2%A0%E6%8B%85"></a>

開発に使用するコンピュータ機器、消耗品等は貴社にて準備すること。

## 貸与物件・資料
<a id="markdown-%E8%B2%B8%E4%B8%8E%E7%89%A9%E4%BB%B6%E3%83%BB%E8%B3%87%E6%96%99" name="%E8%B2%B8%E4%B8%8E%E7%89%A9%E4%BB%B6%E3%83%BB%E8%B3%87%E6%96%99"></a>

開発に使用するコンピュータ機器は、貸与する。

## 納品条件
<a id="markdown-%E7%B4%8D%E5%93%81%E6%9D%A1%E4%BB%B6" name="%E7%B4%8D%E5%93%81%E6%9D%A1%E4%BB%B6"></a>

### 納品物一覧
<a id="markdown-%E7%B4%8D%E5%93%81%E7%89%A9%E4%B8%80%E8%A6%A7" name="%E7%B4%8D%E5%93%81%E7%89%A9%E4%B8%80%E8%A6%A7"></a>

- 基本設計書
- 詳細設計書
- アプリケーションソフトウェア
- テスト仕様書
- テスト結果報告書
- 操作手順書

各XX部

（紙媒体・電子媒体・CD・DVD）

### 納品方法
<a id="markdown-%E7%B4%8D%E5%93%81%E6%96%B9%E6%B3%95" name="%E7%B4%8D%E5%93%81%E6%96%B9%E6%B3%95"></a>

（窓口（住所・電話番号・メールアドレス）持参・郵送（必着）・メール・チャットツール）

# 提案依頼事項
<a id="markdown-%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E4%BA%8B%E9%A0%85" name="%E6%8F%90%E6%A1%88%E4%BE%9D%E9%A0%BC%E4%BA%8B%E9%A0%85"></a>

本RFPに記載した要件を実現するシステムについて、以下の事項を提案すること。

前提条件・制約条件があれば記載すること。

要件を満たさない箇所およびより良い提案があれば差異や理由を記載すること。

## システム全体概要
<a id="markdown-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E6%A6%82%E8%A6%81" name="%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E5%85%A8%E4%BD%93%E6%A6%82%E8%A6%81"></a>

提案するシステムの全体概要図

## 提供機能と実現化方式
<a id="markdown-%E6%8F%90%E4%BE%9B%E6%A9%9F%E8%83%BD%E3%81%A8%E5%AE%9F%E7%8F%BE%E5%8C%96%E6%96%B9%E5%BC%8F" name="%E6%8F%90%E4%BE%9B%E6%A9%9F%E8%83%BD%E3%81%A8%E5%AE%9F%E7%8F%BE%E5%8C%96%E6%96%B9%E5%BC%8F"></a>

提案するシステムに含まれる機能・非機能およびその実現化方式

## 運用条件
<a id="markdown-%E9%81%8B%E7%94%A8%E6%9D%A1%E4%BB%B6" name="%E9%81%8B%E7%94%A8%E6%9D%A1%E4%BB%B6"></a>

ハードウェア・ソフトウェアのバージョン等の前提条件、処理の所要時間

## 開発体制
<a id="markdown-%E9%96%8B%E7%99%BA%E4%BD%93%E5%88%B6" name="%E9%96%8B%E7%99%BA%E4%BD%93%E5%88%B6"></a>

体制図

以下を明記すること
- PMのマネジメント経験年数、プロジェクト実績、経験年数、資格等
- PGのプロジェクト実績、経験年数、資格等

## 開発スケジュール
<a id="markdown-%E9%96%8B%E7%99%BA%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB" name="%E9%96%8B%E7%99%BA%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB"></a>

契約締結から検収までのスケジュール

## 定例報告およびレビュー
<a id="markdown-%E5%AE%9A%E4%BE%8B%E5%A0%B1%E5%91%8A%E3%81%8A%E3%82%88%E3%81%B3%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC" name="%E5%AE%9A%E4%BE%8B%E5%A0%B1%E5%91%8A%E3%81%8A%E3%82%88%E3%81%B3%E3%83%AC%E3%83%93%E3%83%A5%E3%83%BC"></a>

定例会スケジュールおよび議事録の書式

## 開発管理・開発手法・開発言語
<a id="markdown-%E9%96%8B%E7%99%BA%E7%AE%A1%E7%90%86%E3%83%BB%E9%96%8B%E7%99%BA%E6%89%8B%E6%B3%95%E3%83%BB%E9%96%8B%E7%99%BA%E8%A8%80%E8%AA%9E" name="%E9%96%8B%E7%99%BA%E7%AE%A1%E7%90%86%E3%83%BB%E9%96%8B%E7%99%BA%E6%89%8B%E6%B3%95%E3%83%BB%E9%96%8B%E7%99%BA%E8%A8%80%E8%AA%9E"></a>

開発管理手法、開発に使用する言語・開発ツール・支援ツール

## 費用
<a id="markdown-%E8%B2%BB%E7%94%A8" name="%E8%B2%BB%E7%94%A8"></a>

可能な限り詳細な見積り

### 貴社情報
<a id="markdown-%E8%B2%B4%E7%A4%BE%E6%83%85%E5%A0%B1" name="%E8%B2%B4%E7%A4%BE%E6%83%85%E5%A0%B1"></a>

- 会社案内
- 提案責任者名
- 過去の実績
- 過去の類似実績
- 過去3年間の決算書

### 貴社問い合わせ窓口
<a id="markdown-%E8%B2%B4%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3" name="%E8%B2%B4%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3"></a>

- 担当者名
- 住所
- 電話番号
- メールアドレス

# 提案手続き
<a id="markdown-%E6%8F%90%E6%A1%88%E6%89%8B%E7%B6%9A%E3%81%8D" name="%E6%8F%90%E6%A1%88%E6%89%8B%E7%B6%9A%E3%81%8D"></a>

## 参加資格条件
<a id="markdown-%E5%8F%82%E5%8A%A0%E8%B3%87%E6%A0%BC%E6%9D%A1%E4%BB%B6" name="%E5%8F%82%E5%8A%A0%E8%B3%87%E6%A0%BC%E6%9D%A1%E4%BB%B6"></a>

- プライバシーマーク
- ISMS
- 類似システムの開発実績を有していること
- XXX資格の保有者がXX名以上在籍していること

## 提案スケジュール
<a id="markdown-%E6%8F%90%E6%A1%88%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB" name="%E6%8F%90%E6%A1%88%E3%82%B9%E3%82%B1%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB"></a>

| 日程          | 項目               | 備考             |
| ------------- | ------------------ | ---------------- |
| 2023年2月     | 提案依頼           |                  |
| 2023年2月中旬 | RFP説明会・質問会  | ビデオ会議で実施 |
| 2023年2月末   | 提案期限           |                  |
| 2023年3月上旬 | プレゼンテーション | 弊社会議室で実施 |
| 2023年3月中旬 | 選定結果の通知     | 電子メールで連絡 |

## RFP説明会・質問会
<a id="markdown-rfp%E8%AA%AC%E6%98%8E%E4%BC%9A%E3%83%BB%E8%B3%AA%E5%95%8F%E4%BC%9A" name="rfp%E8%AA%AC%E6%98%8E%E4%BC%9A%E3%83%BB%E8%B3%AA%E5%95%8F%E4%BC%9A"></a>

- 日時
- 場所

## 質問期限
<a id="markdown-%E8%B3%AA%E5%95%8F%E6%9C%9F%E9%99%90" name="%E8%B3%AA%E5%95%8F%E6%9C%9F%E9%99%90"></a>

本RFPの内容に関する質問は、別紙X　質問票に記載の上、弊社問い合わせ窓口に提出すること。

## 提案書の提出
<a id="markdown-%E6%8F%90%E6%A1%88%E6%9B%B8%E3%81%AE%E6%8F%90%E5%87%BA" name="%E6%8F%90%E6%A1%88%E6%9B%B8%E3%81%AE%E6%8F%90%E5%87%BA"></a>

（窓口持参・郵送（必着）・メール・チャットツール）

2023年2月28日 17時

## プレゼンテーション
<a id="markdown-%E3%83%97%E3%83%AC%E3%82%BC%E3%83%B3%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3" name="%E3%83%97%E3%83%AC%E3%82%BC%E3%83%B3%E3%83%86%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3"></a>

- 日時
- 場所
- 持ち時間

## 選定結果の連絡
<a id="markdown-%E9%81%B8%E5%AE%9A%E7%B5%90%E6%9E%9C%E3%81%AE%E9%80%A3%E7%B5%A1" name="%E9%81%B8%E5%AE%9A%E7%B5%90%E6%9E%9C%E3%81%AE%E9%80%A3%E7%B5%A1"></a>

電子メールで連絡

## 弊社問い合わせ窓口
<a id="markdown-%E5%BC%8A%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3" name="%E5%BC%8A%E7%A4%BE%E5%95%8F%E3%81%84%E5%90%88%E3%82%8F%E3%81%9B%E7%AA%93%E5%8F%A3"></a>

- 担当部署
- 担当者名
- 住所
- 電話番号
- メールアドレス

# 評価
<a id="markdown-%E8%A9%95%E4%BE%A1" name="%E8%A9%95%E4%BE%A1"></a>

## 評価の方針
<a id="markdown-%E8%A9%95%E4%BE%A1%E3%81%AE%E6%96%B9%E9%87%9D" name="%E8%A9%95%E4%BE%A1%E3%81%AE%E6%96%B9%E9%87%9D"></a>

本RFPに記載の要件を満たしているか、以下の評価基準に沿って公平に選定する。

## 評価項目
<a id="markdown-%E8%A9%95%E4%BE%A1%E9%A0%85%E7%9B%AE" name="%E8%A9%95%E4%BE%A1%E9%A0%85%E7%9B%AE"></a>

| 評価項目                 | 評価のポイント                                               |
| ------------------------ | ------------------------------------------------------------ |
| サービスレベルへの充足度 | サービスレベルを満たしているか                               |
| 機能要件への充足度       | 機能要件を満たしているか                                     |
| 非機能要件への充足度     | 非機能要件を満たしているか                                   |
| 追加提案内容             | 本RFPに記載の要件以外の追加提案の内容を評価し加点する        |
| 提案の実現可能性         | 提案内容が具体的で実現可能性が高いと判断した場合には加点する |
| プロジェクト遂行力       | プロジェクト管理の考え方やPM・PGのスキル・経験               |
| 貴社の実績               | 類似実績の開発実績                                           |
| 価格                     | 提示された価格                                               |

# 契約事項
<a id="markdown-%E5%A5%91%E7%B4%84%E4%BA%8B%E9%A0%85" name="%E5%A5%91%E7%B4%84%E4%BA%8B%E9%A0%85"></a>

## 発注形態
<a id="markdown-%E7%99%BA%E6%B3%A8%E5%BD%A2%E6%85%8B" name="%E7%99%BA%E6%B3%A8%E5%BD%A2%E6%85%8B"></a>

（請負契約・準委任契約・その他）

## 再委託
<a id="markdown-%E5%86%8D%E5%A7%94%E8%A8%97" name="%E5%86%8D%E5%A7%94%E8%A8%97"></a>

## 検収
<a id="markdown-%E6%A4%9C%E5%8F%8E" name="%E6%A4%9C%E5%8F%8E"></a>

### 検収・検査期間について
<a id="markdown-%E6%A4%9C%E5%8F%8E%E3%83%BB%E6%A4%9C%E6%9F%BB%E6%9C%9F%E9%96%93%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6" name="%E6%A4%9C%E5%8F%8E%E3%83%BB%E6%A4%9C%E6%9F%BB%E6%9C%9F%E9%96%93%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6"></a>

納品を受けて、受入テストを実施した後に合否判定を行う。判定結果は受入テスト実施後XX日以内に通知する。

### 作業完了報告書提出年月日について
<a id="markdown-%E4%BD%9C%E6%A5%AD%E5%AE%8C%E4%BA%86%E5%A0%B1%E5%91%8A%E6%9B%B8%E6%8F%90%E5%87%BA%E5%B9%B4%E6%9C%88%E6%97%A5%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6" name="%E4%BD%9C%E6%A5%AD%E5%AE%8C%E4%BA%86%E5%A0%B1%E5%91%8A%E6%9B%B8%E6%8F%90%E5%87%BA%E5%B9%B4%E6%9C%88%E6%97%A5%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6"></a>

受入テスト実施後XX日以内に貴社は作業完了報告書を提出する。

## 支払条件
<a id="markdown-%E6%94%AF%E6%89%95%E6%9D%A1%E4%BB%B6" name="%E6%94%AF%E6%89%95%E6%9D%A1%E4%BB%B6"></a>

貴社の納品書・請求書・作業完了報告書を受領した翌々月末に貴社指定の銀行口座への振込みとする。

振込手数料はXXX負担

## 機密保持契約
<a id="markdown-%E6%A9%9F%E5%AF%86%E4%BF%9D%E6%8C%81%E5%A5%91%E7%B4%84" name="%E6%A9%9F%E5%AF%86%E4%BF%9D%E6%8C%81%E5%A5%91%E7%B4%84"></a>

弊社から提供した資料、情報、問い合わせへの回答等の情報の機密保持のため、別途機密保持契約を締結する。

## 著作権等
<a id="markdown-%E8%91%97%E4%BD%9C%E6%A8%A9%E7%AD%89" name="%E8%91%97%E4%BD%9C%E6%A8%A9%E7%AD%89"></a>

完成したシステムの所有権、著作権、二次的著作物の利用権は対価の支払時点で弊社に帰属または移転される。

## 瑕疵担保・賠償責任
<a id="markdown-%E7%91%95%E7%96%B5%E6%8B%85%E4%BF%9D%E3%83%BB%E8%B3%A0%E5%84%9F%E8%B2%AC%E4%BB%BB" name="%E7%91%95%E7%96%B5%E6%8B%85%E4%BF%9D%E3%83%BB%E8%B3%A0%E5%84%9F%E8%B2%AC%E4%BB%BB"></a>

納品後半年間を瑕疵担保責任期間とする。

## その他
<a id="markdown-%E3%81%9D%E3%81%AE%E4%BB%96" name="%E3%81%9D%E3%81%AE%E4%BB%96"></a>

# 別紙
<a id="markdown-%E5%88%A5%E7%B4%99" name="%E5%88%A5%E7%B4%99"></a>

## 質問票
<a id="markdown-%E8%B3%AA%E5%95%8F%E7%A5%A8" name="%E8%B3%AA%E5%95%8F%E7%A5%A8"></a>