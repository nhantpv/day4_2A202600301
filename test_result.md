venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.rning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: Xin chào, tôi đang muốn đi du lịch nhưng chưa biết đi đâu

TravelBuddy đang suy nghĩ...


TravelBuddy: Chào bạn! Để giúp bạn tìm điểm đến phù hợp, bạn có thể cho tôi biết một số thông tin như: bạn muốn đi đâu, thời gian dự kiến đi, số người cùng đi, và ngân sách bạn dự định?

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: tôi muốn đi du lịch, gợi ý

TravelBuddy đang suy nghĩ...

Trả lời trực tiếp

TravelBuddy: Bạn có thể cho mình biết điểm đến mà bạn muốn đi, ngân sách dự kiến và thời gian du lịch không? Điều này giúp mình gợi ý cho bạn những phương án phù hợp nhất.

Bạn: Đà Nẵng, 5 triệu, 5 ngày tới

TravelBuddy đang suy nghĩ...

Trả lời trực tiếp

TravelBuddy: Bạn có thể cho tôi biết bạn sẽ khởi hành từ thành phố nào được không?

Bạn: Hà Nội

TravelBuddy đang suy nghĩ...


TravelBuddy: Xin bạn vui lòng cho biết điểm đến tiếp theo của bạn là gì? Ngoài ra, bạn có ngân sách khoảng bao nhiêu và số người đi? điều này sẽ giúp tôi tìm kiếm thông tin chính xác hơn cho bạn.       

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: Xin chào! Tôi đang muốn đi du lịch nhưng chưa biết đi đâu

TravelBuddy đang suy nghĩ...

Trả lời trực tiếp

TravelBuddy: Xin chào! Bạn có một số điểm đến nào trong đầu chưa? Nếu chưa, tôi có thể gợi ý cho bạn 
một số địa điểm đẹp ở Việt Nam như Đà Nẵng, Hội An, Phú Quốc, Nha Trang hoặc Hà Nội. Bạn cũng có thể 
cho tôi biết ngân sách cho chuyến đi để tôi tìm những lựa chọn phù hợp hơn!

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: Tìm giúp tôi chuyến bay từ Hà Nội đi Đà Nẵng  

TravelBuddy đang suy nghĩ...

Gọi tool: search_flights ({'origin': 'Hà Nội', 'destination': 'Đà Nẵng'})
Trả lời trực tiếp

TravelBuddy: Chuyến bay từ Hà Nội đi Đà Nẵng có các lựa chọn như sau:

1. **Vietnam Airlines**
   - Giờ bay: 06:00 → 07:20
   - Hạng: Economy
   - Giá: 1.450.000đ

2. **Vietnam Airlines**
   - Giờ bay: 14:00 → 15:20
   - Hạng: Business
   - Giá: 2.800.000đ

3. **VietJet Air**
   - Giờ bay: 08:30 → 09:50
   - Hạng: Economy
   - Giá: 890.000đ

4. **Bamboo Airways**
   - Giờ bay: 11:00 → 12:20
   - Hạng: Economy
   - Giá: 1.200.000đ

Nếu bạn cần thêm thông tin về khách sạn hoặc ngân sách, hãy cho tôi biết nhé!

  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: Tôi ở Hà Nội, muốn đi Phú Quốc 2 đêm, budget 5 triệu, tư vấn giúp tôi

TravelBuddy đang suy nghĩ...

Trả lời trực tiếp

TravelBuddy: Để giúp bạn lập kế hoạch chuyến đi từ Hà Nội đến Phú Quốc trong 2 đêm với ngân sách 5 triệu, mình cần tìm hiểu thêm về các chi phí như vé máy bay và khách sạn. Mình sẽ tìm chuyến bay và khách sạn phù hợp với ngân sách đó.
Xin cho mình biết bạn có thể chi bao nhiêu cho mỗi đêm ở khách sạn nhé!

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: tôi muốn đặt khách sạn

TravelBuddy đang suy nghĩ...

Trả lời trực tiếp

TravelBuddy: Bạn có thể cho tôi biết điểm đến và ngân sách của bạn cho mỗi đêm không? Điều này sẽ giú

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

(venv) PS C:\Users\PC\Downloads\lab4_agent> python agent.py
C:\Users\PC\Downloads\lab4_agent\venv\Lib\site-packages\langchain_core\_api\deprecation.py:25: UserWarning: Core Pydantic V1 functionality isn't compatible with Python 3.14 or greater.
  from pydantic.v1.fields import FieldInfo as FieldInfoV1
============================================================
TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

TravelBuddy – Trợ lý Du lịch Thông minh
Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

Gõ 'quit' để thoát
============================================================

Bạn: giải giúp tôi bài tập python về linked list

============================================================

Bạn: giải giúp tôi bài tập python về linked list

Bạn: giải giúp tôi bài tập python về linked list

TravelBuddy đang suy nghĩ...

TravelBuddy đang suy nghĩ...
TravelBuddy đang suy nghĩ...


Trả lời trực tiếp

TravelBuddy: Xin lỗi, nhưng tôi chỉ chuyên về du lịch và không thể trợ giúp về lập trình hay các bài tập học thuật khác. Nếu bạn có câu hỏi nào liên quan đến điểm đến, ngân sách hay kế hoạch du lịch, hãy cho 
tôi biết nhé!

Bạn: Traceback (most recent call last):
  File "C:\Users\PC\Downloads\lab4_agent\agent.py", line 78, in <module>
    user_input = input("\nBạn: ").strip()
                 ~~~~~^^^^^^^^^^^
KeyboardInterrupt
(venv) PS C:\Users\PC\Downloads\lab4_agent>