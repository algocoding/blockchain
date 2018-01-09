============================
이더리움
============================



Smart Contract
=============================================




Solidity lang.
=============================================

Solidity 언어는 스마트 계약을 기술하기 위한 언어이다. 

계약이라고 하면...



.. code-block:: solidity

    pragma solidity ^0.4.0;

    contract SimpleStorage {            # 계약명
        uint storedData;

        function set(uint x) public {
            storedData = x;
        }

        function get() public constant returns (uint) {
            return storedData;
        }
    }




.. tip::

    이더리움 관련 정보는 이더리움홈_ 에서 확인할 수 있다.






.. _이더리움홈: https://www.ethereum.org/ 
