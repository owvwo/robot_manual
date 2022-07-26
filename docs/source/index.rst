# [표준 현장 설치 절차서] 
 로봇 설치에 대한 표준 현장 설치는 아래 순서대로 
*********

1. (현장) 로봇설치 (연동라벨링 기준) 및 개통처리 

2. (현장->관제/선도요원) 로봇 소프트웨어 설치 요청  
    ```sh
    로봇소프트웨어: release-22.02
    KT-agent: 1.5.2 
    ```
    - KT-agent는 기본적으로 **상용 버전** 설치 _(예외 경우는 협의 필요)_

3. (현장-> KTDS) 맵업로드 (최초 및 목적지 수정시) 

    현장용 로보케어앱에서 가능, RM에서 가능 (일정 확인 필요) 

4. (연동사) 정상 연동확인 

5. (현장) 연동동작 테스트 
 
**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
