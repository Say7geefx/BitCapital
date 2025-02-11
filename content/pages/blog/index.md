---
title: Tracking Number
slug: /blog
numOfPostsPerPage: 0
enableSearch: false
topSections: []
styles:
  title:
    textAlign: center
seo:
  metaTitle: Blog - Demo site
  metaDescription: >-
    This is the blog of the demo site where we post about technology, product,
    and design.
  socialImage: /images/img-placeholder.svg
  type: Seo
type: PostFeedLayout
bottomSections: []
---
import "./globals.css"
import type { Metadata } from "next"
import { Inter } from "next/font/google"
import type React from "react" // Import React

const inter = Inter({ subsets: \["latin"] })

export const metadata: Metadata = {
title: "Swift Courier - Track Your Package",
description:
"Swift Courier offers fast and reliable package delivery services. Track your package easily with our online tracking system.",
}

export default function RootLayout({
children,
}: {
children: React.ReactNode
}) {
return (

{children}

)
}
