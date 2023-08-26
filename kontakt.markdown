---
layout: page
title: Kontakt
permalink: /kontakt/
---

Ośrodek szkolenia kierowców "Lidka"  
Lidia Gieroń  ul. Krzyżowa 33  
41-500 Chorzów  
tel. [+48 797 534 203](tel:+48797534203)  
[biuro@osk-lidka.pl](mailto:biuro@osk-lidka.pl)

{% assign h = site.data.office_hours %}

<table>
    <thead>
        <tr>
            <th>Dzień tygodnia</th>
            <th>Godziny otwarcia</th>
        </tr>
    </thead>
    <tdata>
        <tr>
            <td>poniedziałek</td>
            {% if h.monday_open != "" %}
            <td>{{ h.monday_open }} – {{ h.monday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>wtorek</td>
            {% if h.tuesday_open != "" %}
            <td>{{ h.tuesday_open }} – {{ h.tuesday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>środa</td>
            {% if h.tuesday_open != "" %}
            <td>{{ h.wednesday_open }} – {{ h.wednesday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>czwartek</td>
            {% if h.thursday_open != "" %}
            <td>{{ h.thursday_open }} – {{ h.thursday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>piątek</td>
            {% if h.friday_open != "" %}
            <td>{{ h.friday_open }} – {{ h.friday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>sobota</td>
            {% if h.saturday_open != "" %}
            <td>{{ h.saturday_open }} – {{ h.saturday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
        <tr>
            <td>niedziela</td>
            {% if h.sunday_open != "" %}
            <td>{{ h.sunday_open }} – {{ h.sunday_close }}</td>
            {% else %}
            <td>nieczynne</td>
            {% endif %}
        </tr>
    </tdata>
</table>

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2548.047079267315!2d18.94169277693517!3d50.30971349748672!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4716d261e30d814d%3A0x7b8ad7214cb50967!2sO%C5%9Brodek%20Szkolenia%20Kierowc%C3%B3w%20%22LIDKA%22%20Lidia%20Giero%C5%84!5e0!3m2!1spl!2spl!4v1686745437204!5m2!1spl!2spl" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

Dane do przelewu:

ING Bank Śląski S.A.  
49 1050 1243 1000 0090 7045 2975  
O.S.K. „LIDKA” Lidia Gieroń  
ul. Krzyżowa 33  
41-500 Chorzów
