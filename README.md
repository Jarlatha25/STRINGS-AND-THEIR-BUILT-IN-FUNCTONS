# STRINGS-AND-THEIR-BUILT-IN-FUNCTONS
text = &quot; Hello Python World! &quot;
print(&quot;Length:&quot;, len(text))
print(&quot;Uppercase:&quot;, text.upper())
print(&quot;Lowercase:&quot;, text.lower())
print(&quot;Trimmed:&quot;, text.strip())
print(&quot;Replace &#39;Python&#39; with &#39;Programming&#39;:&quot;, text.replace(&quot;Python&quot;, &quot;Programming&quot;))
print(&quot;Count of &#39;o&#39;:&quot;, text.count(&quot;o&quot;))
print(&quot;Starts with &#39;Hello&#39;:&quot;, text.strip().startswith(&quot;Hello&quot;))

print(&quot;Ends with &#39;World!&#39;:&quot;, text.strip().endswith(&quot;World!&quot;))
words = text.strip().split()
print(&quot;Words:&quot;, words)
print(&quot;Joined with &#39;-&#39;:&quot;, &quot;-&quot;.join(words))
Output:
Length: 23
Uppercase: HELLO PYTHON WORLD!
Lowercase: hello python world!
Trimmed: Hello Python World!
Replace &#39;Python&#39; with &#39;Programming&#39;: Hello Programming World!
Count of &#39;o&#39;: 3
Starts with &#39;Hello&#39;: True
Ends with &#39;World!&#39;: True
Words: [&#39;Hello&#39;, &#39;Python&#39;, &#39;World!&#39;]
Joined with &#39;-&#39;: Hello-Python-World!
