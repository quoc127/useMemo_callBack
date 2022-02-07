useCallback : Trả ra một memoized function
useCallback thì tập trung giải quyết vấn đề về performance, khi mà các callback function được tạo ở functional component cha pass xuống component con luôn bị tạo mới, khiến cho con luôn bị re-render.
--
useMemo : Trả ra một memoized value
useMemo tập trung vào việc tránh lặp đi lặp lại các logic tính toán nặng nề.
--
link tham khảo : https://kysumattien.com/the-ultimate-guide-about-useMemo-and-useCallback