---
id: help
title: Help
slug: /help
---

/**
 * Copyright (c) 2017-present, Facebook, Inc.
 *
 * This source code is licensed under the MIT license found in the
 * LICENSE file in the root directory of this source tree.
 */

const React = require("react");

const CompLibrary = require("../../core/CompLibrary.js");

const Container = CompLibrary.Container;
const GridBlock = CompLibrary.GridBlock;

function Help(props) {
  const { config: siteConfig, language = "" } = props;
  const { baseUrl, docsUrl } = siteConfig;
  const docsPart = `${docsUrl ? `${docsUrl}/` : ""}`;
  const langPart = `${language ? `${language}/` : ""}`;
  const docUrl = (doc) => `${baseUrl}${docsPart}${langPart}${doc}`;

  return (
    <div className="docMainWrapper wrapper">
      <Container className="mainContainer documentContainer postContainer">
        <div className="post">
          <header className="postHeader">
            <h1>Can't find what you're looking for?</h1>
          </header>

          <p>
            If our <a href="/docs/">documentation</a> doesn't answer your
            questions, here are a few options for contacting us:
          </p>

          <strong>Email Us</strong>
          <p>
            You can contact us via {" "}
            <a href="mailto:%69%6e%66%6f%40%68%75%62%73%66%6f%75%6e%64%61%74%69%6f%6e%2e%6f%72%67">
              email
            </a>{" "}. 
            {/* You can{" "}
            <a href="mailto:%69%6e%66%6f%40%68%75%62%73%66%6f%75%6e%64%61%74%69%6f%6e%2e%6f%72%67">
              get subscription support,
            </a>{" "}
            ask{" "}
            <a href="mailto:%69%6e%66%6f%40%68%75%62%73%66%6f%75%6e%64%61%74%69%6f%6e%2e%6f%72%67">
              questions about hubs cloud,
            </a>{" "}
            or contact us about{" "}
            <a href="mailto:%69%6e%66%6f%40%68%75%62%73%66%6f%75%6e%64%61%74%69%6f%6e%2e%6f%72%67">
