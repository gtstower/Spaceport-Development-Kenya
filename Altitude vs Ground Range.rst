stk.v.11.0
WrittenBy    STK_v11.2.0

BEGIN ReportStyle

BEGIN ClassId
	Class		LaunchVehicle
END ClassId

BEGIN Header
	StyleType		0
	Title		Altitude vs Ground Range
	Date		Yes
	Name		Yes
	IsHidden		No
	DescShort		No
	DescLong		No
	YLog10		No
	Y2Log10		No
	YUseWholeNumbers		No
	Y2UseWholeNumbers		No
	VerticalGridLines		No
	HorizontalGridLines		No
	AnnotationType		Spaced
	NumAnnotations		3
	NumAngularAnnotations		5
	ShowYAnnotations		Yes
	AnnotationRotation		1
	BackgroundColor		#ffffff
	ForegroundColor		#000000
	ViewableDuration		3600.000000
	RealTimeMode		No
	DayLinesStatus		1
	LegendStatus		1
	LegendLocation		1

BEGIN PostProcessor
	Destination	0
	Use	0
	Destination	1
	Use	0
	Destination	2
	Use	0
	Destination	3
	Use	0
END PostProcessor
	NumSections		1
END Header

BEGIN Section
	Name		Section 1
	ClassName		LaunchVehicle
	NameInTitle		No
	ExpandMethod		0
	PropMask		2
	ShowIntervals		No
	NumIntervals		0
	NumLines		1

BEGIN Line
	Name		Line 1
	NumElements		3

BEGIN Element
	Name		Time
	IsIndepVar		Yes
	IndepVarName		Time
	Title		Time
	NameInTitle		No
	Service		GroundRange
	Type		Fixed
	Element		Time
	SumAllowedMask		0
	SummaryOnly		No
	DataType		0
	UnitType		2
	LineStyle		0
	LineWidth		0
	PointStyle		0
	PointSize		0
	FillPattern		0
	LineColor		#000000
	FillColor		#000000
	PropMask		0
	UseScenUnits		Yes
END Element

BEGIN Element
	Name		Ground Range-Fixed-Ground Range
	IsIndepVar		No
	IndepVarName		Time
	Title		Ground Range
	NameInTitle		Yes
	Service		GroundRange
	Type		Fixed
	Element		Ground Range
	SumAllowedMask		1559
	SummaryOnly		No
	DataType		0
	UnitType		0
	LineStyle		0
	LineWidth		0
	PointStyle		0
	PointSize		0
	FillPattern		0
	LineColor		#000000
	FillColor		#000000
	PropMask		0
	UseScenUnits		Yes
END Element

BEGIN Element
	Name		Ground Range-Fixed-Alt
	IsIndepVar		No
	IndepVarName		Time
	Title		Alt
	NameInTitle		Yes
	Service		GroundRange
	Type		Fixed
	Element		Alt
	SumAllowedMask		1559
	SummaryOnly		No
	DataType		0
	UnitType		0
	LineStyle		0
	LineWidth		0
	PointStyle		0
	PointSize		0
	FillPattern		0
	LineColor		#000000
	FillColor		#000000
	PropMask		0
	UseScenUnits		Yes
END Element
END Line
END Section

BEGIN LineAnnotations
END LineAnnotations
END ReportStyle

