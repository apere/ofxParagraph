ofxParagraph
-----------------
A simple paragraph renderer for [openFrameworks](http://openframeworks.cc/) that allows you to set the alignment, width, indentation, leading and pixel based word spacing of paragraphs. It also supports font caching.


![image](./img/layout-example.png)

#### CONSTRUCTOR
-----------------

	ofxParagraph paragraph = ofxParagraph(string text, int width, ofxParagraph::alignment align)

------------------------------------------------------------------------------

#### PUBLIC METHODS
 
	void draw()

	void setText(string text)
	
	void setFont(string file, int pointSize) 

	void setWidth(int width)
	
	int getWidth()
	
	int getHeight()
 
	void setColor(ofColor color)
	
	void setColor(int color) // e.g. 0x333333
 
	void setAlignment(ofxParagraph::alignment align)
	
	void setPosition(ofPoint position)	
 
	void setIndent(int indent)
 
	void setLeading(int leading)
 
	void setSpacing(int spacing)
	
	void drawBorder(bool draw)
	
	void drawBorder(ofColor color)
	
	void setBorderPadding(int padding)

	void drawWordBoundaries(bool draw)

