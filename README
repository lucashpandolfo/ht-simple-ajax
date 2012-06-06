HT-SIMPLE-AJAX 0.4 + Experimental JSON support

Usage
=====

JSON ajax request
```lisp
(defun-ajax say-hi (name) (*ajax-processor* :json)
  (format nil "{ greeting:'Hello', name:'~a'}" name))
```

XML ajax requests
```lisp
(defun-ajax say-hi (name) (*ajax-processor* :xml)
  (format nil "Hello ~a" name))
```

```lisp
(defun-ajax say-hi (name) (*ajax-processor*)
  (concatenate 'string "Hi " name ", nice to meet you."))
```

