# Credit-Scoring

## Описание проекта:
Цель данного проекта - построение скоринговой модели, которая позволит максимизировать совокупную экономическую прибыль (в процентах от суммы выдачи). Скоринговая модель получает на вход значения факторов, на выходе выдает ответ, нужно ли выдавать данный заем.

Задача модели состоит в том, чтобы выдавать на основе факторов займы таким образом, чтобы % экономической прибыли был максимальным.

Значение экономической прибыли считается следующим образом:
- Loss = Unpaid * (EL, expected loss)
- InvestorProfit = Earned — Loss
- Profit = InvestorProfit + Commission
- Profit% = Profit / LoanIssued

## *English version*

## Description
The purpose of this project is to build a scoring model that will maximize the total economic profit (as a percentage of the loan amount). The scoring model takes factor values as input and outputs an answer whether the loan should be made.

The task of the model is to issue loans based on the factors in such a way that the % of economic profit is maximized.

The value of economic profit is calculated as follows:
- Loss = Unpaid * (EL, expected loss)
- InvestorProfit = Earned — Loss
- Profit = InvestorProfit + Commission
- Profit% = Profit / LoanIssued
