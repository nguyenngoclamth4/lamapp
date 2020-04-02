# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version : ruby '2.7.0', rails '6.0.2.1'

* Database creation
    B1: sudo -i -u postgres
    B2: create database SAMPLE_DB;

* Database initialization
    B1: rails db:migrate
        order_id: not null = no
        card_id: not null = no
    B2: rails db:seed