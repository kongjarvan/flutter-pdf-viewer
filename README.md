syncfusion pdf viewer


###############dependency###################

dependencies:
  flutter:
    sdk: flutter
  syncfusion_flutter_pdfviewer: ^21.1.38

############### 사용법 ###################

  late PdfViewerController _pdfViewerController; // 컨트롤러 선언
  final GlobalKey<SfPdfViewerState> _pdfViewerStateKey = GlobalKey(); // 키 선언
  
    @override
  void initState() {
    _pdfViewerController = PdfViewerController();
    _pdfViewerController.zoomLevel = 1; // 배율 설정
    super.initState();
  }

  
  
 SfPdfViewer 위젯을 통해 pdf 파일을 읽을 수 있음.
  
  위젯에 대한 자세한 내용은 https://pub.dev/packages/syncfusion_flutter_pdfviewer/install 에서 확인 가능
  
