---
title: Alert Info
category: Application
paid: false
isActive: true
ltr: {"vue":{"vueCss":[{"label":"App.vue","code":"<template>\n  <div class=\"alert-info\">\n    <div class=\"alert-container\">\n      <div class=\"alert\">\n        <div class=\"alert-icon\">\n          <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n            <path fillRule=\"evenodd\"\n              d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\"\n              clipRule=\"evenodd\" />\n          </svg>\n        </div>\n        <div class=\"alert-details\">\n          <span class=\"lable\">\n            Info\n          </span>\n          <div class=\"details-container\">\n            <div class=\"details\">\n              New sales from the last subscribers - 20K USD in revenue.\n            </div>\n            <div class=\"link-container\">\n              <a href=\"javascript:void(0)\" class=\"link\">\n                Details\n                <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                  <path fillRule=\"evenodd\"\n                    d=\"M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z\"\n                    clipRule=\"evenodd\" />\n                </svg>\n              </a>\n            </div>\n          </div>\n        </div>\n      </div>\n      <button class=\"hide-btn\">\n        <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n          <path fillRule=\"evenodd\"\n            d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\"\n            clipRule=\"evenodd\" />\n        </svg>\n      </button>\n    </div>\n  </div>\n</template>"},{"code":".alert-info {\n  margin: 3rem 1rem 0px 1rem;\n  padding: 0px 1rem 0px 1rem;\n  border-radius: 0.375rem;\n  background-color: #eff6ff;\n}\n\n@media (min-width: 768px) {\n  .alert-info {\n    max-width: 42rem;\n    margin-left: auto;\n    margin-right: auto;\n  }\n}\n\n.alert-info .alert-container {\n  display: flex;\n  justify-content: space-between;\n  padding: 0.75rem 0px 0.75rem 0px;\n}\n\n.alert-info .alert-container .alert {\n  display: flex;\n}\n\n.alert-info .alert-container .alert .alert-icon svg {\n  width: 1.5rem;\n  height: 1.5rem;\n  color: #60a5fa;\n}\n\n.alert-info .alert-container .alert .alert-details {\n  align-self: center;\n  margin-left: 0.75rem;\n  color: #3b82f6;\n}\n\n.alert-info .alert-container .alert .alert-details .lable {\n  font-weight: 600;\n}\n\n.alert-info .alert-container .alert .alert-details .details-container .details {\n  margin-top: 0.25rem;\n}\n\n.alert-info .alert-container .alert .alert-details .details-container .link-container {\n  margin-top: 0.75rem;\n}\n\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link {\n  display: flex;\n  align-items: center;\n  font-weight: 500;\n  text-decoration: underline;\n  font-size: 0.875rem;\n  line-height: 1.25rem;\n}\n\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link svg {\n  width: 0.875rem;\n  height: 0.875rem;\n  margin-left: 0.25rem;\n}\n\n.alert-info .alert-container .hide-btn {\n  align-self: flex-start;\n  color: #3b82f6;\n}\n\n.alert-info .alert-container .hide-btn svg {\n  width: 1.25rem;\n  height: 1.25rem;\n}","label":"style.css"}],"vueTail":[{"label":"App.vue","code":"<template>\n  <div class=\"mt-12 mx-4 px-4 rounded-md bg-blue-50 md:max-w-2xl md:mx-auto\">\n    <div class=\"flex justify-between py-3\">\n      <div class=\"flex\">\n        <div>\n          <svg xmlns=\"http://www.w3.org/2000/svg\" class=\"h-6 w-6 text-blue-400\" viewBox=\"0 0 20 20\"\n            fill=\"currentColor\">\n            <path fillRule=\"evenodd\"\n              d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\"\n              clipRule=\"evenodd\" />\n          </svg>\n        </div>\n        <div class=\"self-center ml-3\">\n          <span class=\"text-blue-500 font-semibold\">\n            Info\n          </span>\n          <div class=\"text-blue-500\">\n            <div class=\"mt-1\">\n              New sales from the last subscribers - 20K USD in revenue.\n            </div>\n            <div class=\"mt-2\">\n              <a href=\"javascript:void(0)\" class=\"flex items-center text-sm font-medium underline\">\n                Details\n                <svg xmlns=\"http://www.w3.org/2000/svg\" class=\"h-3.5 w-3.5 ml-1\" viewBox=\"0 0 20 20\"\n                  fill=\"currentColor\">\n                  <path fillRule=\"evenodd\"\n                    d=\"M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z\"\n                    clipRule=\"evenodd\" />\n                </svg>\n              </a>\n            </div>\n          </div>\n        </div>\n      </div>\n      <button class=\"self-start text-blue-500\">\n        <svg xmlns=\"http://www.w3.org/2000/svg\" class=\"h-5 w-5\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n          <path fillRule=\"evenodd\"\n            d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\"\n            clipRule=\"evenodd\" />\n        </svg>\n      </button>\n    </div>\n  </div>\n</template>"}]},"preview":"function App() {\n  return /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-12 mx-4 px-4 rounded-md bg-blue-50 md:max-w-2xl md:mx-auto md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex justify-between py-3\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex\"\n  }, /*#__PURE__*/React.createElement(\"div\", null, /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6 text-blue-400\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\",\n    clipRule: \"evenodd\"\n  }))), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"self-center ml-3\"\n  }, /*#__PURE__*/React.createElement(\"span\", {\n    className: \"text-blue-500 font-semibold\"\n  }, \"Info\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"text-blue-500\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-1\"\n  }, \"New sales from the last subscribers - 20K USD in revenue.\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-2\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center text-sm font-medium underline\"\n  }, \"Details\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-3.5 w-3.5 ml-1\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  }))))))), /*#__PURE__*/React.createElement(\"button\", {\n    className: \"self-start text-blue-500\"\n  }, /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-5 w-5\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })))));\n}","react":{"jsxCss":[{"label":"App.jsx","code":"export default () => {\n    return (\n        <div className=\"alert-info\">\n            <div className=\"alert-container\">\n                <div className=\"alert\">\n                    <div className=\"alert-icon\">\n                        <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                            <path fillRule=\"evenodd\" d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\" clipRule=\"evenodd\" />\n                        </svg>\n                    </div>\n                    <div className=\"alert-details\">\n                        <span className=\"lable\">\n                            Info\n                        </span>\n                        <div className=\"details-container\">\n                            <div className=\"details\">\n                                New sales from the last subscribers - 20K USD in revenue.\n                            </div>\n                            <div className=\"link-container\">\n                                <a \n                                    href=\"javascript:void(0)\" \n                                    className=\"link\"\n                                >\n                                    Details\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fillRule=\"evenodd\" d=\"M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                    </div>\n                </div>\n                <button className=\"hide-btn\">\n                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                    </svg>\n                </button>\n            </div>\n        </div>\n    )\n}\n"},{"label":"style.css","code":".alert-info {\n  margin: 3rem 1rem 0px 1rem;\n  padding: 0px 1rem 0px 1rem;\n  border-radius: 0.375rem;\n  background-color: #eff6ff;\n}\n@media (min-width: 768px) {\n  .alert-info {\n    max-width: 42rem;\n    margin-left: auto;\n    margin-right: auto;\n  }\n}\n.alert-info .alert-container {\n  display: flex;\n  justify-content: space-between;\n  padding: 0.75rem 0px 0.75rem 0px;\n}\n.alert-info .alert-container .alert {\n  display: flex;\n}\n.alert-info .alert-container .alert .alert-icon svg {\n  width: 1.5rem;\n  height: 1.5rem;\n  color: #60a5fa;\n}\n.alert-info .alert-container .alert .alert-details {\n  align-self: center;\n  margin-left: 0.75rem;\n  color: #3b82f6;\n}\n.alert-info .alert-container .alert .alert-details .lable {\n  font-weight: 600;\n}\n.alert-info .alert-container .alert .alert-details .details-container .details {\n  margin-top: 0.25rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container {\n  margin-top: 0.75rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link {\n  display: flex;\n  align-items: center;\n  font-weight: 500;\n  text-decoration: underline;\n  font-size: 0.875rem;\n  line-height: 1.25rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link svg {\n  width: 0.875rem;\n  height: 0.875rem;\n  margin-left: 0.25rem;\n}\n.alert-info .alert-container .hide-btn {\n  align-self: flex-start;\n  color: #3b82f6;\n}\n.alert-info .alert-container .hide-btn svg {\n  width: 1.25rem;\n  height: 1.25rem;\n}\n"}],"jsxTail":[{"code":"export default () => {\n    return (\n        <div className=\"mt-12 mx-4 px-4 rounded-md bg-blue-50 md:max-w-2xl md:mx-auto md:px-8\">\n            <div className=\"flex justify-between py-3\">\n                <div className=\"flex\">\n                    <div>\n                        <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6 text-blue-400\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                            <path fillRule=\"evenodd\" d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\" clipRule=\"evenodd\" />\n                        </svg>\n                    </div>\n                    <div className=\"self-center ml-3\">\n                        <span className=\"text-blue-500 font-semibold\">\n                            Info\n                        </span>\n                        <div className=\"text-blue-500\">\n                            <div className=\"mt-1\">\n                                New sales from the last subscribers - 20K USD in revenue.\n                            </div>\n                            <div className=\"mt-2\">\n                                <a \n                                    href=\"javascript:void(0)\" \n                                    className=\"flex items-center text-sm font-medium underline\">\n                                    Details\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-3.5 w-3.5 ml-1\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fillRule=\"evenodd\" d=\"M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                    </div>\n                </div>\n                <button className=\"self-start text-blue-500\">\n                    <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-5 w-5\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                    </svg>\n                </button>\n            </div>\n        </div>\n    )\n}","label":"App.jsx"}]}}
rtl: {"react":{"jsxTail":[{"code":"export default () => {\n    return (\n        <div className=\"mt-12 mx-4 px-4 rounded-md bg-blue-50 md:max-w-2xl md:mx-auto md:px-8\">\n            <div className=\"flex justify-between py-3\">\n                <div className=\"flex\">\n                    <div>\n                        <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6 text-blue-400\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                            <path fillRule=\"evenodd\" d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\" clipRule=\"evenodd\" />\n                        </svg>\n                    </div>\n                    <div className=\"self-center mr-3\">\n                        <span className=\"text-blue-500 font-semibold\">\n                            معلومات\n                        </span>\n                        <div className=\"text-blue-500\">\n                            <div className=\"mt-1\">\n                                مبيعات جديدة من المشتركين السابقين - 20000$ في الإيرادات.\n                            </div>\n                            <div className=\"mt-2\">\n                                <a \n                                    href=\"javascript:void(0)\" \n                                    className=\"flex items-center text-sm font-medium underline\">\n                                    تفاصيل\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" class=\"h-3.5 w-3.5 mr-1\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fill-rule=\"evenodd\" d=\"M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z\" clip-rule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                    </div>\n                </div>\n                <button className=\"self-start text-blue-500\">\n                    <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-5 w-5\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                    </svg>\n                </button>\n            </div>\n        </div>\n    )\n}\n","label":"App.jsx"}],"jsxCss":[{"label":"App.jsx","code":"export default () => {\n    return (\n        <div className=\"alert-info\">\n            <div className=\"alert-container\">\n                <div className=\"alert\">\n                    <div className=\"alert-icon\">\n                        <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                            <path fillRule=\"evenodd\" d=\"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\" clipRule=\"evenodd\" />\n                        </svg>\n                    </div>\n                    <div className=\"alert-details\">\n                        <span className=\"lable\">\n                            معلومات\n                        </span>\n                        <div className=\"details-container\">\n                            <div className=\"details\">\n                                مبيعات جديدة من المشتركين السابقين - 20000$ في الإيرادات.\n                            </div>\n                            <div className=\"link-container\">\n                                <a \n                                    href=\"javascript:void(0)\" \n                                    className=\"link\"\n                                >\n                                    تفاصيل\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                        <path fill-rule=\"evenodd\" d=\"M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z\" clip-rule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                    </div>\n                </div>\n                <button className=\"hide-btn\">\n                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                        <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                    </svg>\n                </button>\n            </div>\n        </div>\n    )\n}"},{"code":".alert-info {\n  margin: 3rem 1rem 0px 1rem;\n  padding: 0px 1rem 0px 1rem;\n  border-radius: 0.375rem;\n  background-color: #eff6ff;\n}\n@media (min-width: 768px) {\n  .alert-info {\n    max-width: 42rem;\n    margin-left: auto;\n    margin-right: auto;\n  }\n}\n.alert-info .alert-container {\n  display: flex;\n  justify-content: space-between;\n  padding: 0.75rem 0px 0.75rem 0px;\n}\n.alert-info .alert-container .alert {\n  display: flex;\n}\n.alert-info .alert-container .alert .alert-icon svg {\n  width: 1.5rem;\n  height: 1.5rem;\n  color: #60a5fa;\n}\n.alert-info .alert-container .alert .alert-details {\n  align-self: center;\n  margin-right: 0.75rem;\n  color: #3b82f6;\n}\n.alert-info .alert-container .alert .alert-details .lable {\n  font-weight: 600;\n}\n.alert-info .alert-container .alert .alert-details .details-container .details {\n  margin-top: 0.25rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container {\n  margin-top: 0.75rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link {\n  display: flex;\n  align-items: center;\n  font-weight: 500;\n  text-decoration: underline;\n  font-size: 0.875rem;\n  line-height: 1.25rem;\n}\n.alert-info .alert-container .alert .alert-details .details-container .link-container .link svg {\n  width: 0.875rem;\n  height: 0.875rem;\n  margin-right: 0.25rem;\n}\n.alert-info .alert-container .hide-btn {\n  align-self: flex-start;\n  color: #3b82f6;\n}\n.alert-info .alert-container .hide-btn svg {\n  width: 1.25rem;\n  height: 1.25rem;\n}","label":"style.css"}]},"vue":{"vueTail":[],"vueCss":[]},"preview":"function App() {\n  return /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-12 mx-4 px-4 rounded-md bg-blue-50 md:max-w-2xl md:mx-auto md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex justify-between py-3\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex\"\n  }, /*#__PURE__*/React.createElement(\"div\", null, /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6 text-blue-400\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z\",\n    clipRule: \"evenodd\"\n  }))), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"self-center mr-3\"\n  }, /*#__PURE__*/React.createElement(\"span\", {\n    className: \"text-blue-500 font-semibold\"\n  }, \"\\u0645\\u0639\\u0644\\u0648\\u0645\\u0627\\u062A\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"text-blue-500\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-1\"\n  }, \"\\u0645\\u0628\\u064A\\u0639\\u0627\\u062A \\u062C\\u062F\\u064A\\u062F\\u0629 \\u0645\\u0646 \\u0627\\u0644\\u0645\\u0634\\u062A\\u0631\\u0643\\u064A\\u0646 \\u0627\\u0644\\u0633\\u0627\\u0628\\u0642\\u064A\\u0646 - 20000$ \\u0641\\u064A \\u0627\\u0644\\u0625\\u064A\\u0631\\u0627\\u062F\\u0627\\u062A.\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-2\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center text-sm font-medium underline\"\n  }, \"\\u062A\\u0641\\u0627\\u0635\\u064A\\u0644\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    class: \"h-3.5 w-3.5 mr-1\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    \"fill-rule\": \"evenodd\",\n    d: \"M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z\",\n    \"clip-rule\": \"evenodd\"\n  }))))))), /*#__PURE__*/React.createElement(\"button\", {\n    className: \"self-start text-blue-500\"\n  }, /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-5 w-5\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })))));\n}"}
slug: /alerts
id: 1f7efdad-dc2f-49a8-9cdf-33daaccc81a4
created_at: 1
---