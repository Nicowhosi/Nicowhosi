if (0 == strncmp(lasttext->c_str(), text.c_str(), text.length())) {
 logDebug(u8"last text repeated");
 seek += 100;
}

delete lasttext;
lasttext = new std::string(hi);
