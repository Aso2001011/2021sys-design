```uml
@startuml
start
:weather=代入;
if(weather)then(0)
:快晴です;
elseif then(1)
:曇りです;
elseif then(2)
:雨です;
else
:不明です;
endif
end
@enduml
```
