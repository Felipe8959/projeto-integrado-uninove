Projeto final do 4° semestre de Ciências da Computação - Uninove.
Este projeto contém um ambiente de teste de tração e alongamento à ruptura em fios e cabos elétricos conforme a norma NBR NM 247-3.

Foi utilizdo um servidor Flask (Python) para interagir com as rotas e com o banco de dados e alguns scripts para realização dos cálculos necessários em JavaScript.

Banco de dados: SQLite.

Bibliotecas:
from flask import Flask, render_template, request, redirect, url_for, session, jsonify
from flask_login import LoginManager, UserMixin
import sqlite3
from openpyxl import load_workbook
import os
