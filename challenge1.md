```uml
@startuml
start
:weather=代入;
if(weather)then(0)
:快晴です;
else if(weathter)then(1)
:曇りです;
else if(weather)then(2)
:雨です;
else
:不明です;
endif
end
@enduml
```
