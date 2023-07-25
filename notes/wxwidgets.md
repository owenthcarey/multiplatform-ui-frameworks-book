- https://docs.wxwidgets.org/3.2/page_screenshots.html
- https://docs.wxwidgets.org/3.0/page_class_cat.html

| wxWidgets    | Linux (GTK+)         | macOS (Cocoa)       | Windows (WinAPI)             |
|--------------|----------------------|----------------------|------------------------------|
| wxFrame      | GtkWindow            | NSWindow             | HWND with WS_OVERLAPPEDWINDOW|
| wxDialog     | GtkDialog            | NSPanel              | HWND with WS_OVERLAPPED      |
| wxButton     | GtkButton            | NSButton             | HWND with button class       |
| wxStaticText | GtkLabel             | NSTextField          | HWND with static class       |
| wxTextCtrl   | GtkEntry / GtkTextView | NSTextField / NSTextView | HWND with edit class    |
| wxCheckBox   | GtkCheckButton       | NSButton (checkbox type) | HWND with button class (BS_CHECKBOX style) |
| wxRadioButton| GtkRadioButton       | NSButton (radio button type) | HWND with button class (BS_RADIOBUTTON style) |
| wxListBox    | GtkListBox           | NSListView           | HWND with listbox class      |
| wxComboBox   | GtkComboBox          | NSComboBox           | HWND with combobox class     |
| wxSlider     | GtkScale             | NSSlider             | HWND with trackbar class      |
| wxStatusBar  | GtkStatusBar         | NSStatusBar          | HWND with statusbar class    |
| wxMenuBar    | GtkMenuBar           | NSMenu               | HMENU                        |
